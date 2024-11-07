# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 07/11/2024
Empresa: Abstergo Industries 
Responsável: Thiago Lima

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Thiago Lima. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon Lambda
- Ferramenta Serverless para execução de códigos.
- Pode ser usada para implementação de um algoritmo de cargas e envios dos produtos.

Etapa 2: 
- Amazon Aurora
- Banco de Dados Relacional, Serverless, compatível com MySQL.
- Podemos usar em conjunto com a Lambda para armazenar os dados de pedidos e de entregas.

Etapa 3: 
- Amazon SNS
- Serviço de Notificações.
- Podemos utilizá-lo com conjunto com as duas ferramentas acima, para que, no momento em que uma venda dor concluída, os dados são armazenados no banco e o SNS consome essa info e pode enviar SMSs ou e-mails com as informações, para que ações sejam tomadas.



## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a criação de um microsserviço de mensageria, o que fará gastar menos com armazenamento e com a manutenção de Data Centers. Essa implementação visa eliminar um investimento inicial alto com infraestrutura e passa a ser um custo variável, uma vez que pagarão somente pelo que for utilizado, isso que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

Assinatura do Responsável pelo Projeto:

Thiago Lima
