# Iniciando o uso do git

Criamos inicialmente o repositorio no github (web).

Clonamos o repositorio do github para a nosa maquina utilizando o comando "git clone"

O fluxo normalmente é:
- criar novos arquivos no projeto
- salvar as alteracoes
- versionar essas alteracoes a partir do commit
- sicronizar tudo o que fizemos com o nosso repositorio remoto

Como fizemos o git clone nao precisamos executar o comando "init".

Verificamos o status atual:
$ git status

Fazemos o nosso commit (feito localmente):
$ git commit -m "arquivo iniciando o uso criado"

Definimos as configuracoes locais (credenciais) para conseguirmos enviar
$ git config user.name <username>
$ git config user.email <email>

Para listarmos as configuracoes
$ git config --list

Para enviarmos as alteracoes para o repositorio
$ git push

Atualizando o diretorio local, trazendo o que tem de novo do github para a nossa maquina
$ git pull

Para verificarmos todos os commits realizados ate o momento:
$ git log

Em seguida ligamos o nosso repositório remoto com o repositório local



Criamos o arquivo readme.md onde normalmente informos a razão da existência desse repositório.

Arquivos com extensão .md são vistos de forma especial pelo github,

É interessante todo projeto ter o arquivo de readme.md detalhando pontos importantes daquele projeto.
