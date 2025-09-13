# Diagrama-de-ordem-de-serviço-em-uma-oficina-mecânica.
Esse repositório tem o objetivo de enviar um diagrama de um sistema de ordem de serviço para o projeto de uma oficina mecânica detalhando o controle de clientes, veículos, pedidos, peças, serviços, equipes e pagamentos.
# Foi criado um sistema de tabelas devidamente organizadas e divididas por funções.
---
Os clientes vão até a oficina mecânica para solicitar serviços de consertos, trocas de peças ou apenas manutenções.
Cada cliente pode ter um ou mais veículos e também poderá solicitar mais de um serviço se assim desejar.
Os veículos dos clientes contêm placa, modelo, marca e ano.
Os serviços ofertados pela oficina são dividos por duas categorias consertos que podem ou não incluir troca de peças e manutenções.
Os mecânicos que farão os serviços são divididos em equipes, cada equipe é formada de acordo com a sua especialidade.
Uma equipe especializada em consertos e trocas de peças será responsável por efetuar a ordem do pedido e pela realização dos serviços da sua especialização.
Já a outra equipe especializada em manutenção de veículos será responsável pelos pedidos de manutenções.
Os pedidos contêm a descrição, o estatus, a quantidade, a data de emissão, a data de conclusão, a identificação do cliente que fez o pedido do serviço e o valor.
As ordens de serviços de cada equipe são emitidas com a descrição do serviço a qual cada equipe foi designada contendo o valor, a data, a quantidade, a identificação do pedido e da equipe que realizará o serviço e no caso do serviço de troca de peças também contém o estoque e o nome da peça.
Na aréa do pagamento estão contidas informações sobre a identificação do pedido, a data, o valor total a ser pago, e a forma de pagamento.
