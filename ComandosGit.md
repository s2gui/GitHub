# Comandos do Git

## Limpar a tela
Ele vai apagar todas as mensagens.
```
cls
```

## Listar configurações globais
Vai listar todas as configurações que o Git que conseguir encontrar naquele momento.

git config --list

## Configurar nome de usuário global
definir valores de configuração para o Git em nível global ou local.

git config --global user.name "seunome"

## Configurar email de usuário global
Define valores de configuração para o Git em nível global ou local.

git config --global user.email "seu@gmail.com"

## Verificar o status do repositório
Exibe as condições do diretório de trabalho e da área de staging

git status

## Realizar o primeiro commit
Leva as mudanças de um ambiente local para o repositório no git, permitindo ainda a inserção de uma mensagem descritiva.

git commit -m "Primeiro commit: Adicionado"

## Criar a branch 'main' no repositório remoto
git push -u origin main

## Iniciar um novo repositório Git
git init

## Mudar a branch local de 'master' para 'main'
git branch -M main

## Adicionar todos os arquivos ao índice
git add .

## Adicionar o repositório remoto como 'origin' com o seu link do Git
git remote add origin "link do seu git"

## Fazer push para a branch 'main' no repositório remoto
git push -u origin main

## Add arquivo dentro do VS
Para adicionar um novo arquivo ou pasta dentro do VS Code
git pull

# Para entrar na sua branch
git checkout branch01/nome da sua branch

# Referencias:
[README](README.md)

[py.md](py.md)
