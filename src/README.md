# Automação com Terraform 


## Objetivo do projeto

O objetivo é automatizar o processo de criação e manutenção do ambiente de execução para os projetos de softwares da empresa.

## Premissas do projeto

Para o desenvolvimento do projeto, foram levantadas as seguintes premissas:

+ Utilizar o Terraform como ferramenta de IAC
+ O cluster Kubernetes deve ser criado utilizando o serviço EKS (Elastic Kubernetes Service) da AWS.
+ O projeto deve ser o mais simples e reproveitável possível.
+ Todas vez que houver alteração no código Terraform na branch main do repositório, a pipeline deve ser executada.
+ Só vai haver um ambiente Kubernetes (os ambientes de desenvolvimento, homologação e produção serão separados por namespace).

## Tecnologias utilizadas:

+ [AWS](https://aws.amazon.com/)
    [S3](http://aws.amazon.com/s3/)
    [EKS](https://aws.amazon.com/eks/)

##

![Diagrama  do projeto](/diagramas/arquitetura_cloud_aws.drawio.png)

