# padr-es-para-o-versionamento


## Visão Geral

A ideia principal do Conventional Commits é estruturar as mensagens de commit de uma maneira consistente para facilitar a geração automática de notas de lançamento e o versionamento semântico.
Aqui estão alguns elementos-chave dessa convenção:

* Tipos:

  - Define a natureza do commit, como feat para uma nova funcionalidade, fix para correção de bugs, chore para tarefas de manutenção, etc.

* Âmbito (Opcional):

  - Indica a área do código afetada pelo commit. Pode ser algo como user, auth, docs, etc.

* Descrição:

  - Breve resumo do que foi feito.

**Exemplo de mensagem de commit usando o Conventional Commits:**

- `feat(user): adiciona suporte para autenticação via biometria`

Essa mensagem indica que foi adicionada uma nova funcionalidade relacionada ao usuário, que é a autenticação via OAuth.

Além do Conventional Commits, existem outras convenções como Angular Commit Message Conventions, Semantic Commit Messages, entre outras. 
A escolha entre elas depende da preferência da equipe e das necessidades do projeto.



## Tipos

- **`feat` (Feature):**
  - Adiciona uma nova funcionalidade.
  - Exemplo: `feat(user): adiciona suporte para autenticação via biometria`

- **`fix` (Fix):**
  - Corrige bugs.
  - Exemplo: `fix(auth): resolve problema de vazamento de memória na autenticação`

- **`chore` (Chore):**
  - Tarefas de manutenção, refatoração, etc.
  - Exemplo: `chore(docs): atualiza documentação de API`

- **`docs` (Documentation):**
  - Alterações na documentação.
  - Exemplo: `docs(readme): adiciona instruções de instalação`

- **`style` (Style):**
  - Mudanças que não afetam a lógica do código.
  - Exemplo: `style(code): ajusta indentação no arquivo de configuração`

- **`refactor` (Refactor):**
  - Refatora código existente sem alterar funcionalidade.
  - Exemplo: `refactor(auth): simplifica lógica de autenticação`

- **`test` (Test):**
  - Adições ou modificações nos testes.
  - Exemplo: `test(api): adiciona teste de unidade para serviço de usuário`

- **`ci` (Continuous Integration):**
  - Mudanças em configurações ou scripts de integração contínua.
  - Exemplo: `ci(travis): configura pipeline para deploy automático`

Sinta-se à vontade para adicionar ou adaptar tipos de commit conforme necessário.

## Contribuição

Seja feliz contribuindo a vontade para este projeto.

## Licença

Este projeto não é licenciado .
