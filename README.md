## Aprenda Git

### 📗 Índice:

- [Roteiro de aprendizado](#roteiro-de-aprendizado)
- [Leitura recomendada](#leitura-recomendada)

### Roteiro de aprendizado
> Nota: **não** será explicado como instalar o Git, utilize algum mecanismo de
pesquisa. De preferência, pesquise como configurar o Git no seu sistema
operacional.

##### Não esqueça: É **muito importante** que você crie arquivos enquanto segue a leitura, utilizando os comandos mostrados.

1. [Fundamentos do Git](./src/basico.md)
   - O que é Git e por que usá-lo?
   - Configuração inicial: `git config`
   - Criando um repositório: `git init`

2. [Trabalhando com commits](./src/commits.md)
   - Adicionando arquivos: `git add`
   - Criando commits: `git commit`
   - Verificando o status: `git status`

3. [Histórico e logs](./src/historico.md)
   - Visualizando o histórico: `git log`
   - Diferenças entre commits: `git diff`
   - Desfazendo alterações: `git checkout`, `git reset`

4. [Trabalhando com branches](./src/branches.md)
   - Criando e trocando de branch: `git branch`, `git checkout`
   - Merge de branches: `git merge`
   - Resolvendo conflitos

5. [Trabalhando com repositórios remotos](./src/remotos.md)
   - Adicionando um repositório remoto: `git remote add`
   - Enviando e recebendo alterações: `git push`, `git pull`
   - Clonando um repositório: `git clone`
   - Usando `git fetch` em vez de `git pull`

6. [Tags e versões](./src/tags.md)
   - Criando tags: `git tag`
   - Trabalhando com versões estáveis

7. [Boas práticas e workflows](./src/boas-praticas.md)
   - Mensagens de commit claras
   - Git Flow
   - Rebase vs Merge

8. [Comandos avançados](./src/avancado.md)
   - Stash: `git stash`
   - Rebase interativo: `git rebase -i`

9. [Resolução de problemas comuns](./src/problemas.md)
    - Desfazendo commits indesejados
    - Recuperando arquivos deletados
    - Lidando com conflitos complexos

### Leitura recomendada

- Pro Git
    - Livro gratuito e definitivo sobre Git, escrito por Scott Chacon e Ben Straub.
    - Disponível em: [Pro Git](https://git-scm.com/book/en/v2)
