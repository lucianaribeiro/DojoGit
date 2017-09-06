## DOJO GIT | 



## Instalando Git

##### Windows

http://msysgit.github.com

##### Ubuntu

```
sudo apt-get update
sudo apt-get install git 
```



## Comandos Básicos 



Abrindo o terminal

```
Ctrl + Alt + T
```

Acessando diretórios pelo terminal

```
cd nome_diretório
cd ..
```

Criando diretórios pelo terminal

```
mkdir novo_diretório
```

Configurando

```
git config --global user.name "seu_nome_aqui"
git config --global user.email "seu_email@emailx.com"
```

Mostrando as novas configurações

```
git config -l
```

Baixando um repositório

```
git clone https://github.com/respositorioX 
```

Adicionando arquivos para o pŕoximo commit

```
git add nome_arquivo
```

Adicionando todos os arquivos

```
git add .
```

Dando um Commit 

```
git status
git add codigo.java
git commit -m "mensagem"
git push 
```

Baixando atualizações do repositório remoto

```
git pull 
```

Atualizando o repositório remoto

```
git push
```

Criando uma Branch

```
git status
git branch
git checkout -b nova_branch
git push origin nova_branch
```

Mesclando alterações de uma branch com outra

```
git merge nome_branch
```



#### Observações:

1) O terminal é case-sensitive, ou seja, tem diferença entre maiúscula e minúscula

2) Sempre dar pull antes de um commit, evite conflitos 

3) Sempre commitar quando terminar um método, evite conflitos

4) Sempre usar git status 

5) Dúvidas? `git --help`

