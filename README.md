# Desafio DIO - S3 Object Lambda

## Entendendo o Desafio
Este projeto consolida conhecimentos em Lambda Functions e S3, com foco em automação via CloudFormation. O objetivo foi configurar um Object Lambda e documentar a experiência.

## Descrição do Processo
- Baixei o projeto `amazon-s3-object-lambda-default-configuration-main` e naveguei até a pasta `function\nodejs_20_x\release`.
- Envie o arquivo `s3objectlambda_deployment_package.zip` para o bucket `meudesafio-lambda-codigo-2025marcella`.
- Configurei o CloudFormation com o template `s3objectlambda_defaultconfig.yaml`, usando parâmetros como `ObjectLambdaAccessPointName=meu-olap-2025marcella` e `VersionId=TSvjhcp_Mi18_BLKahccp.YCM4aBEhUo`.
- Após ajustes (versionamento, caminhos corretos), o deploy foi bem-sucedido com "CREATE_COMPLETE".

## Insights e Aprendizados
- Importância de ativar versionamento no S3 para CloudFormation.
- Cuidados com caminhos de arquivos e nomes de buckets.
- Uso do GitHub para documentar e compartilhar.

## Recursos Usados
- [Documentação AWS CloudFormation](https://docs.aws.amazon.com/cloudformation/)
- Capturas de tela na pasta `/images`.

## Status
Projeto concluído em 20/09/2025.
