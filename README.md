# Repositório do Bootcamp Orbi Web Games Developer
Tarefas relacionadas ao bootcamp da DIO - Órbi Web Games Developer

## Links úteis:
[Sintaxe basica do Markdown](https://www.markdownguide.org/basic-syntax/)<br>
[Documentação do Git](https://git-scm.com/docs/git/pt_BR)

## Dicas para gerar chave SSH e associar email no Github

*1) Criar chave SSH no GitBash*

$ ssh-keygen -t ed25519 -C “seu email aqui“

*2) Gerar chave para Github*

$ cat id_...   .pub

*3) Copiar e jogar no seu Github*

Entrar na área de configuraçoes .. segurança e criar uma nova chave SSH

*Voltar ao GitBash

*4) Validar no GitBash*

Ativar agente = $ eval $(ssh-agent -s)
Adicionar ao agente = $ ssh-add id_... (sem ser a .pub)

*Comando para verificar se o email e nickname estao associado ao Github:*

Git config --list (Verificar nome e nickname)

Para resetar a configuraçao: Git config --global --unset user.email
                             Git config --global --unset user.nickname

Para associar novamente: Git config --global user.email “seu email do Github”
                         Git config --global user.nickname “Seu nick no Github ”

