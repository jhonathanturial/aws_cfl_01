# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 27/11/2023
Empresa: Abstergo Industries 
Responsável: Jhonathan Turial de Oliveira

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por  Jhonathan Turial. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- EC2 Auto-Scaling
- Provisionar recursos de hardware de acordo com a demanda computacional
- A empresa possui um site de e-commerce varejista e possui uma certa capacidade de instancias provisionadas que supri a necessidade durante o ano, entretanto, na Black-Friday a demanda computacional aumenta causando um sobre-carga nas instâncias, com o Auto-Scaling, as instâncias serão provisionadas e encerradas conforme a demanda de acessos dos usuários.

Etapa 2: 
- S3 Intelligent Tiering
- Otimizar os custos de armazenamento, movendo automaticamente os dados para o nível de acesso mais econômico quando os padrões de acesso mudam
- A empresa possui diversos documentos e notas fiscais para armazenar, desejam um ambiente seguro e com baixo nível de custo. Eles não tem noção de quantas vezes irão necessitar dos prontuários. Para otimização e redução, o intelligent tiering irá armazenar os objetos dentro dos modelos de S3 de acordo com a sua utilização. 

Etapa 3: 
- Elastic File System
- Aumenta e diminui automaticamente conforme você adiciona e remove arquivos, sem a necessidade de gerenciamento ou provisionamento cargas de trabalhos para compartilhamento de arquivos.
- Possuimos mais de uma instancia e precisamos provisionar os arquivos de forma eficiente para as mesma, o EFS gerencia a carga de trabalho que provisiona os arquivos, trazendo eficiência para os serviços



## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado [benefícios das ferramentas]*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

[
    https://aws.amazon.com/ec2/autoscaling/ - Documentação Amazon EC2 Auto Scaling;
    https://aws.amazon.com/pt/efs/ - Documentação Amazon Elastic File System;
    https://aws.amazon.com/s3/storage-classes/intelligent-tiering/ - Documentação S3 Intelligent Tiering;

]

Assinatura do Responsável pelo Projeto:

Jhonathan Turial 