# Contribuição

Obrigado por contribuir com este repositório!  

Siga estas diretrizes para mantermos qualidade, consistência e Clean Code.

---

## Fluxo de Branches (GitFlow)

- main → branch de produção (release estável)
- develop → branch de integração e desenvolvimento
- feature/* → novas funcionalidades
- release/* → preparação de release
- hotfix/* → correção urgente em produção

---

## Commits

Use o padrão Conventional Commits:

- feat(scope): Nova funcionalidade
- fix(scope): Correção de bug
- chore: Tarefa de manutenção ou refatoração
- docs: Alteração na documentação
- test: Adição ou correção de testes

---

## Pull Requests

- Sempre contra a branch develop
- Inclua descrição clara
- Marque revisores (CODEOWNERS)
- Certifique-se que build e testes passam

---

## Testes e qualidade

- Escreva testes unitários e integração
- Execute `dotnet build` e `dotnet test`
- Siga padrões de lint/formatter do projeto

---

## Documentação

- Atualize README.md ou arquivos em /docs sempre que necessário
