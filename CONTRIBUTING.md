
# Guia de Contribuição - GMS

Obrigado por contribuir com o projeto GMS (Gerenciamento de Materiais e Estoque)!

Este documento apresenta as orientações que devem ser seguidas pelos integrantes durante o desenvolvimento do sistema.

## 1. Organização das Branches

O projeto utiliza a seguinte organização:

- `main`: branch que contém a versão estável do sistema.
- `develop`: branch principal de desenvolvimento e integração.

## 2. Fluxo de Desenvolvimento

Para contribuir com o projeto, siga estas etapas:

1. Atualize sua branch `develop` local.
2. Crie uma nova branch a partir de `develop` (git switch -c tipo/nome-do-branch).
3. Realize as alterações necessárias.
4. Teste as modificações realizadas.
5. Faça o commit das alterações (git commit -m "mensagem").
6. Envie a branch para o repositório remoto (git push origin tipo/nome-do-branch).
7. Abra um Pull Request direcionado à branch `develop`.

## 3. Padrão de Commits

As mensagens de commit devem ser claras e objetivas.

Exemplos:

- `:sparkles: feat: adicionar cadastro de produtos`
- `:bug: fix: corrigir validação de estoque`
- `:books: docs: atualizar documentação`
- `:recycle: refactor: organizar código de movimentações`

## 4. Pull Requests

Todo Pull Request deve:

- Possuir uma descrição clara das alterações.
- Referenciar a issue relacionada, quando houver.
- Ser direcionado à branch `develop`.
- Ter suas alterações testadas antes da solicitação de integração.

## 5. Boas Práticas

- Evite enviar arquivos desnecessários ao repositório.
- Não compartilhe senhas, tokens ou credenciais.
- Mantenha o código organizado e legível.
- Evite realizar alterações diretamente na branch `main`.
- Mantenha sua branch atualizada com a `develop`.

## 6. Considerações Finais

Todos os integrantes devem seguir estas orientações para manter a organização, a qualidade e a padronização do desenvolvimento do GMS.
