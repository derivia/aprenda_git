# Trabalhando com Repositórios Remotos

Repositórios remotos são versões do seu projeto hospedadas em servidores
externos, como GitHub ou GitLab.

----------

## Adicionando um repositório remoto

Para "conectar" seu repositório local a um repositório remoto, use o comando `git remote add`.

### Comando:
```bash
git remote add origin <URL-do-repositório>
```

> `origin` é o nome padrão para o repositório remoto, mas você pode usar outro nome.

```mermaid
sequenceDiagram
    participant Local as Repositório Local
    participant Remote as Repositório Remoto

    Local ->> Remote: git remote add origin <URL>
    Note over Local,Remote: Conecta o repositório local ao remoto.
```

----------

## Enviando e recebendo alterações

### Enviando alterações

`git push` envia as alterações do seu repositório local para o repositório remoto.

#### Comando:
```bash
git push origin main
```

- `origin` é o nome do repositório remoto.
- `main` é o nome da branch que você está enviando.

### Recebendo alterações

`git pull` atualiza seu repositório local com as alterações do repositório remoto.

#### Comando:
```bash
git pull origin main
```

- `origin` é o nome do repositório remoto.
- `main` é o nome da branch que você está atualizando.

```mermaid
sequenceDiagram
    participant Local as Repositório Local
    participant Remote as Repositório Remoto

    Local ->> Remote: git push origin main
    Note over Local,Remote: Envia alterações locais para o remoto.
    Remote ->> Local: git pull origin main
    Note over Remote,Local: Recebe alterações do remoto para o local.
```

----------

## Clonando um repositório

Para trabalhar em um projeto existente, você pode clonar um
repositório remoto usando o comando `git clone`.

### Comando:
```bash
git clone <URL-do-repositório>
```

- Isso cria uma cópia local do repositório.

```mermaid
sequenceDiagram
    participant Local as Repositório Local
    participant Remote as Repositório Remoto

    Remote ->> Local: git clone <URL>
    Note over Remote,Local: Cria uma cópia local do repositório remoto.
```

----------

[Cap. Anterior](./branches.md) - [Próx. Capítulo](./tags.md)
