# PRINCIPAIS CÓDIGOS :computer:

_Códigos que utilizo no meu dia a dia de estudos._

> 🔹 git init
> Inicializa o git criando o repositório local vazio.

> 🔹 git config - -global user.email <e-mail cadastrado>
>  git config - -global user.name <username>
> Informa ao git qual o e-mail e o nome, para que haja um autor atrelado.

> 🔹 git config - -list
> Lista todas as configurações do seu git.

> 🔹 git config - -global --unset user.email || user.name
> Caso precise alterar o e-mail ou username, depois é só configurar novamente.

> 🔹 git add .  || git add *
> Adiciona e prepara os arquivos novos e modified para serem commitados.

> 🔹 git commit -m “messenger”
> Adiciona um commit e coloca os arquivos no staging.

> 🔹 git log
> Para achar a chave de um commit.

> 🔹 git revert <chave do commit>
> Para reverter algum commit errado, desfaz o commit indicado.

> 🔹 git reset -- hard (descarta o commit e as alterações no arquivo) || -- soft (descarta os commits, mas deixa os arquivos locais) <chave do commit que será o ponto de retorno>
> Resetar alterações e voltar ao commit indicado, tudo que foi feito depois do commit indicado será desfeito e o history alterado.

> 🔹 git commit -- amend
> Editar o último commit antes do push.
> 1- Digita <i> para abrir a edição e corrige o erro;
> 2- Esc e digita <:wq>

> 🔹 git remote add origin <link do repositório>
> Indica para o git para onde o repositório local será enviado. (Só é necessário na 1ª vez)

> 🔹 git push -u origin <nome da branch>
> Empurra o repositório local para o remoto.

> 🔹 git pull origin <nome da branch>
> Puxa para o repositório local as alterações feitas direto no github.

> 🔹 git clone <link do repositório remoto>
> Baixar um repositório remoto para a máquina.

> 🔹 git checkout -b <nome>
> Cria uma nova branch.

> 🔹 git checkout <nome>
> Navegar para outra branch.

> 🔹 git branch -m <novo nome>
> Renomeia a current branch.

> 🔹 git merge <nome da outra branch>
> Unir as alterações de outras branchs à principal.
