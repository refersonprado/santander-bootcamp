# Versionamento de código com Git e GitHub

## 📘 Documentação
| Git                       | GitHub                      |
|---------------------------|-----------------------------|
| [Clique para abrir](https://git-scm.com/docs/) | [Clique para abrir](https://docs.github.com/pt) |

## 🖥️ Resumos
- Para inicililizar um projeto podemos utilizar o __`$ git init`__.
___
- Para verificar status do git o __`$ git status`__.
___
- Para verificar os logs dos seus commits utilize o  __`$ git log`__.
___
- Para adicionar arquivos utiliza o __`git add NOME_ARQUIVO`__ ou caso queria subir todos os arquivos  __`git add .`__.
___
- Para conectar a um projeto remoto utiliza o seguinte comando:
    
    __`$ git remote add origin https://github.com/username/nome-do-repositorio.git`__
___
- Para fazer commits pode utilizar __`$ git commit -m "mensagem do commit"`__.
___
- Para alterar um commit temos duas possibilidades

    Alterar com uma visualização mais completa  __`$ git commit --amend`__ 

    Para alterar apenas o commit direto __`$ git commit --amend –m "nova mensagem"`__ 
___
- Para desfazer commits temos algumas opções
    - __`$ git reset`__
    - __`$ git reset --soft`__
    - __`$ git reset --mixed`__
    - __`$ git reset --hard`__
___
- Para pegar um arquivo do repositorio remoto para local utiliza-se o  __`$ git push -u <nome do remote> <nome da branch>`__
___
- Já para pegar um arquivo local e levar para o remoto usa o __`$ git pull -u <nome do remote> <nome da branch>`__
