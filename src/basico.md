# Fundamentos do Git

## O que é Git e por que usá-lo?

Git é um sistema de controle de versão distribuído, usado para rastrear
mudanças em arquivos e coordenar trabalho entre várias pessoas. Ele é
amplamente utilizado no desenvolvimento de software, mas pode ser aplicado a
qualquer tipo de projeto que envolva arquivos.

- Por que usar Git:
    - Controle de versão: Mantém um histórico de todas as alterações.
    - Colaboração: Facilita o trabalho em equipe, permitindo que várias
    pessoas trabalhem no mesmo projeto.
    - Backup: Cada clone de um repositório Git é um backup completo do
    projeto.

## Configuração inicial

Antes de começar a usar o Git, é importante configurar seu ambiente. O comando
`git config` permite definir configurações como nome e e-mail.

Exemplos de configuração:
```bash
git config --global user.name "<seu-nome>"
git config --global user.email "<seu-email>"
```

## Criando um repositório

Para começar a usar o Git em um projeto, você precisa criar um repositório. O
comando `git init` inicializa um novo repositório no diretório atual.

Passos para criar um repositório:
1. Navegue até o diretório do projeto.
2. Execute o comando `git init`.

```bash
cd /caminho/do/projeto
git init
```

[Próx. Capítulo](./commits.md)
