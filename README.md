# Estudos de git

Centralizo aqui minhas anotações dos estudos realizados de `git`.

## `git diff`

Comando para verificar os arquivos modificados na alteração.

```
git diff
```

## `git add`

Comando para adicionar arquivos em `staged`.

**A `staging area` é o conjunto de arquivos cujas mudanças serão incluídas na nova versão.**

Adicionando todos os arquivos modificados em staging:

```
git add .
```

Adicionando um arquivo específico:

```
git add . path_file
```

Serve para adicionar os arquivos em staging no nivel do path
**Obs: Estudar mais esse comando e ver se de fato é útil**

```
git add -p path_file
```

## `git log`

Serve para ver os últimos `commits` que foram realizados no repositório.

```
git log
```
