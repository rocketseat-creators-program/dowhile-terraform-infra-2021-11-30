<img src="https://storage.googleapis.com/golden-wind/experts-club/capa-github.svg" />

# Configurando sua infraestrutura com Terraform

Nessa aula iremos implementar uma infraestrutura na AWS utilizando os serviços SQS e S3. Com o auxilio do Terraform, iremos criar todos esses serviços utilizando linhas de códigos. Além disso, vamos configurar também um evento de notificação para que toda vez que um arquivo seja adicionado no bucket S3, a fila SQS seja notificada.

## Links úteis

- [Terraform Tutorials](https://learn.hashicorp.com/terraform?utm_source=terraform_io&utm_content=terraform_io_hero)
- [Terraform Registry](https://registry.terraform.io/)

## Requisitos necessários

- [AWS Account](https://aws.amazon.com/free/)
- [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html)
- [Terraform CLI](https://learn.hashicorp.com/tutorials/terraform/install-cli?in=terraform/aws-get-started)

## Ambiente e recursos necessários

- Seu editor de código de preferência (No meu caso, Visual Studio Code);
- Vontade de aprender :D

## Comandos utilizados
- terraform init
- terraform validate
- terraform apply
- terraform show
- terraform destroy