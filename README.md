# Marcar Horário Online

Aplicativo de agendamento da **Barbearia Ferreira**, feito em um único arquivo `index.html` com HTML, CSS e JavaScript puros.

## Como usar

Abra `index.html` em um navegador. Escolha o serviço, o dia e um horário disponível. Preencha nome do tutor, nome do pet e telefone, e confirme. A confirmação mostra serviço, dia, início, fim e preço.

## Regras de horários

- Calendário com navegação entre meses; domingos e datas passadas ficam indisponíveis.
- Horários de 30 em 30 minutos, das 9h às 18h, sem atendimento das 12h às 13h.
- Um serviço só pode começar quando toda a sua duração couber antes do almoço ou até as 18h, sem conflitar com outro agendamento.
- Cada agendamento ocupa todos os blocos de 30 minutos da sua duração. Os blocos ocupados ficam desabilitados.
- No dia atual, horários passados não são exibidos. As datas usam o horário local.

## Limitação

Os agendamentos ficam apenas na memória da página. Ao recarregar ou fechar a página, eles desaparecem. Não há sincronização entre visitantes, banco de dados ou envio para o estabelecimento.

A lista de serviços ainda contém os serviços originais do pet shop e pode ser atualizada para os serviços da barbearia.
