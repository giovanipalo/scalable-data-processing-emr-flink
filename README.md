# Projeto de Processamento de Dados com AWS EMR e Apache Flink

Este projeto tem como propósito desenvolver uma solução robusta e escalável para o processamento de dados, aproveitando as capacidades do AWS EMR (Elastic MapReduce) e do framework Apache Flink. O objetivo principal é automatizar a configuração e o gerenciamento da infraestrutura necessária para executar pipelines de processamento de dados em lote e streaming, capazes de lidar com grandes volumes de dados com baixa latência.

## Objetivos

- Automatizar o provisionamento da infraestrutura de engenharia de dados utilizando IaC (Infrastructure as Code) com Terraform.
- Utilizar o AWS EMR para execução de clusters Hadoop e Spark, proporcionando escalabilidade e capacidade de processamento distribuído.
- Integrar o Apache Flink para processamento de streaming de dados em tempo real, garantindo baixa latência e alto desempenho.
- Desenvolver pipelines de dados em batch e streaming para ingestão, transformação e análise de grandes volumes de dados.

## Funcionalidades

- **Provisionamento Automatizado**: Utilização do Terraform para configurar e gerenciar a infraestrutura necessária na AWS, incluindo clusters EMR, redes e armazenamento.
  
- **Processamento em Lote**: Implementação de pipelines de processamento de dados em lotes usando Apache Flink sobre clusters EMR, permitindo a análise eficiente de grandes volumes de dados.

- **Processamento em Streaming**: Desenvolvimento de pipelines de dados em tempo real com Apache Flink, para processamento contínuo de dados, garantindo baixa latência e capacidade de resposta imediata a eventos.

- **Monitoramento e Logging**: Configuração de ferramentas de monitoramento e logging para os clusters EMR e aplicações Apache Flink, assegurando visibilidade e controle sobre o estado e desempenho dos pipelines.

## Arquitetura

O projeto é baseado na seguinte arquitetura:

- **AWS EMR**: Utilizado para criar clusters Hadoop e Spark gerenciados, oferecendo escalabilidade automática e integração com outros serviços AWS.
  
- **Apache Flink**: Framework de processamento distribuído para implementação de pipelines de dados em tempo real, com suporte a alto throughput e baixa latência.

- **Terraform**: Utilizado para IaC, provisionando infraestrutura na AWS de maneira automatizada e replicável.

## Requisitos

- Conta na AWS com permissões para criação de recursos como EMR, EC2, VPC, IAM, etc.
- Instalação local do Terraform para gerenciar o provisionamento da infraestrutura.

## Execução do Projeto

Para utilizar este projeto:

1. Clone o repositório.
2. Configure suas credenciais AWS localmente ou utilize perfis configurados.
3. Utilize o Terraform para aplicar as configurações definidas nos arquivos de infraestrutura (`terraform apply`).
4. Implemente seus pipelines de dados utilizando Apache Flink sobre clusters EMR provisionados.

## Utilização do Docker

Para este projeto, o Docker foi integrado ao ambiente Linux (Ubuntu) para otimizar o desenvolvimento e assegurar um ambiente consistente e eficiente. Utilizando contêineres Docker, conseguimos garantir a portabilidade dos aplicativos, facilitando a configuração e o gerenciamento de dependências.
