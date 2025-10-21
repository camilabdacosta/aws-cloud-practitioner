# ⚙️ Anotações: Tarefas Automatizadas com AWS Lambda e S3

Este repositório reúne anotações e aprendizados adquiridos durante o laboratório de consolidação de conhecimentos em tarefas automatizadas utilizando AWS Lambda e Amazon S3.

## 🧩 Conceitos Fundamentais

- **AWS Lambda**: Serviço de computação serverless que executa código em resposta a eventos, sem necessidade de provisionar servidores.
- **Amazon S3**: Serviço de armazenamento de objetos altamente escalável e durável, ideal para armazenar arquivos, logs e dados de entrada/saída.
- **Integração Lambda + S3**: Permite executar funções automaticamente quando objetos são criados, modificados ou excluídos em buckets S3.

## 🔄 Fluxo de Automação Típico

1. Upload de um arquivo em um bucket S3
2. Evento de criação aciona uma função Lambda
3. A função processa o arquivo (ex: redimensiona imagem, extrai metadados, grava logs)
4. Resultados são armazenados em outro bucket ou banco de dados (ex: DynamoDB)

## 🛠️ Boas Práticas

- Criar funções Lambda com escopo mínimo de permissões (princípio do menor privilégio)
- Utilizar variáveis de ambiente para configurar comportamentos dinâmicos
- Monitorar execuções com Amazon CloudWatch Logs
- Testar localmente com ferramentas como AWS SAM ou LocalStack
- Documentar o fluxo de eventos e dependências entre serviços

## ⚠️ Erros Comuns

- Falta de permissões no IAM para leitura/escrita no S3
- Eventos mal configur