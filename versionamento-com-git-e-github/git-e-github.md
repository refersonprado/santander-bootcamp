# Versionamento de código com Git e GitHub

## 📘 Documentação

| Git                                            | GitHub                                          |
| ---------------------------------------------- | ----------------------------------------------- |
| [Clique para abrir](https://git-scm.com/docs/) | [Clique para abrir](https://docs.github.com/pt) |

## 🖥️ Resumos

- Para inicililizar um projeto podemos utilizar o **`$ git init`**.

---

- Para verificar status do git o **`$ git status`**.

---

- Para verificar os logs dos seus commits utilize o **`$ git log`**.

---

- Para adicionar arquivos utiliza o **`git add NOME_ARQUIVO`** ou caso queria subir todos os arquivos **`git add .`**.

---

- Para conectar a um projeto remoto utiliza o seguinte comando:
  **`$ git remote add origin https://github.com/username/nome-do-repositorio.git`**

---

- Para fazer commits pode utilizar **`$ git commit -m "mensagem do commit"`**.

---

- Para alterar um commit temos duas possibilidades

  Alterar com uma visualização mais completa **`$ git commit --amend`**

  Para alterar apenas o commit direto **`$ git commit --amend –m "nova mensagem"`**

---

- Para desfazer commits temos algumas opções
  - **`$ git reset`**
  - **`$ git reset --soft`**
  - **`$ git reset --mixed`**
  - **`$ git reset --hard`**

---

- Para pegar um arquivo do repositorio remoto para local utiliza-se o **`$ git push -u <nome do remote> <nome da branch>`**

---

- Já para pegar um arquivo local e levar para o remoto usa o **`$ git pull -u <nome do remote> <nome da branch>`**
