# Passo a passo do projeto
 
## Criar projeto no VSCode

Criar um projeto. Sugestão aula-git.

## Instalar extensões no VSCode
 1. aguardar um pouco
 2. instalar depois para instalar quem tem mais de 10mi de downloads

## Inicializar umm projeto com git - git init

Rodar no terminal

```sh
git init
```

Perceba que o VSCode já destaca a integração com o GIT.


## Adicionando arquivos - git add
Os arquivos ainda sâo classificados como não rastreáveis(untraked)

Para eles comemeçarem a ser monitorados pelo git eles precisam ir para a área de staging. O comando:

```sh
git add *
```

O * é um coringa para adicionar tudo

## Persistir mudanças - git commit

Para persistir as mudanças, usamos o comando:
```sh
git commit -m 'feat-novo documento da aula'
```