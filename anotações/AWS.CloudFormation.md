# 🧠 Anotações: Laboratório AWS CloudFormation

Este documento reúne os principais aprendizados e observações durante o laboratório de implementação da primeira Stack com AWS CloudFormation.

## 📌 Conceitos Fundamentais

- **CloudFormation**: Ferramenta da AWS para gerenciar infraestrutura como código (IaC), utilizando arquivos YAML ou JSON.
- **Stack**: Conjunto de recursos AWS gerenciados como uma única unidade.
- **Template**: Documento que define os recursos da Stack, incluindo parâmetros, recursos e saídas.

## 🛠️ Boas Práticas

- Validar o template antes da criação com `aws cloudformation validate-template`.
- Utilizar parâmetros para tornar o template reutilizável e flexível.
- Documentar cada recurso com comentários explicativos no YAML.
- Organizar o repositório com README, imagens e arquivos separados por função.
- Registrar aprendizados e dificuldades para referência futura.

## ⚠️ Erros Comuns

- Permissões insuficientes no IAM para criação de recursos.
- Sintaxe incorreta no YAML (atenção à indentação e estrutura).
- Referência incorreta de parâmetros ou nomes de recursos.

## 📚 Ferramentas Utilizadas

- AWS Console e AWS CLI
- GitHub para versionamento e documentação
- VS Code para edição dos templates

## 📝 Observações Pessoais

- A prática reforça a importância da automação e padronização na criação de ambientes.
- O uso de `Outputs` no template facilita a visualização de dados importantes após a criação da Stack.
- A documentação clara é essencial para reuso e compartilhamento do conhecimento.

## 🔗 Referências Úteis

- [Documentação AWS CloudFormation](https://docs.aws.amazon.com/cloudformation/)
- [Guia de Markdown no GitHub](https://guides.github.com/features/mastering-markdown/)
- [GitHub Quick Start](https://github.com/git-guides)

