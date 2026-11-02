# Marcar Horário Online

Aplicativo de agendamento da **Barbearia Ferreira**, feito em um único arquivo `index.html` com HTML, CSS e JavaScript puros.

## Serviços

| Serviço | Duração | Preço de referência |
| --- | --- | ---: |
| Corte masculino | 1h | R$ 50 |
| Corte e barba | 2h | R$ 80 |
| Barba | 30 min | R$ 35 |
| Acabamento | 30 min | R$ 20 |

Os preços são referências e podem variar conforme a cidade e o estabelecimento. Foram escolhidos com base na [pesquisa do Procon-PE de 2025](https://www.procon.pe.gov.br/images/2025/pesquisa/PESQUISA-DE-PRECOS-SUGESTOES-DE-PRESENTES-_DIA-DOS-PAIS-2025.pdf) e na [tabela da Cruz Barbearia](https://cruzbarbearia.com/precos/).

## Como usar

Abra `index.html` em um navegador. Escolha o serviço, o dia e um horário disponível. Informe seu nome e telefone e confirme. A confirmação mostra serviço, dia, início, fim e preço.

## Regras de horários

- Calendário com navegação entre meses; domingos e datas passadas ficam indisponíveis.
- Horários de 30 em 30 minutos, das 9h às 18h, sem atendimento das 12h às 13h.
- Um serviço só pode começar quando toda a sua duração couber antes do almoço ou até as 18h, sem conflitar com outro agendamento.
- Cada agendamento ocupa todos os blocos de 30 minutos da sua duração. Os blocos ocupados ficam desabilitados.
- No dia atual, horários passados não são exibidos. As datas usam o horário local.

## Limitação atual

Os agendamentos ficam apenas na memória da página. Ao recarregar ou fechar a página, eles desaparecem. Eles não são compartilhados entre visitantes. A persistência em um servidor ainda não está configurada.
