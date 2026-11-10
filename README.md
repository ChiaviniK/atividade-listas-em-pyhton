# 📦 Gerenciador de Produtos e Preços em Python

Este projeto é uma aplicação simples e interativa desenvolvida em Python para gerenciar um catálogo de produtos e seus respectivos preços. Ideal para praticar manipulação de listas, laços de repetição e interações com o usuário.

## 🚀 Funcionalidades

O sistema está dividido em três partes principais:
1. **Visualização Inicial**: Exibição dos produtos e preços atualmente cadastrados no catálogo.
2. **Cadastro Interativo**: Permite ao usuário inserir um novo produto e seu respectivo preço, atualizando a base de dados dinamicamente.
3. **Remoção de Itens**: Remove o último produto cadastrado para controle e ajuste rápido do catálogo.

---

## 🛠️ Tecnologias Utilizadas

* **Python 3.x**
* Conceitos aplicados:
  * Estruturas de dados (`list`)
  * Laço de repetição (`for` junto com a função `zip`)
  * Entrada e saída de dados (`input` e `print` formatado)
  * Métodos de lista (`append` e `pop`)

---

## 📖 Como Funciona o Código

### 1. Exibição do Catálogo
O código percorre as listas de produtos e preços simultaneamente usando `zip()` para apresentar as informações formatadas:
```python
for i, j in zip(produtos, precos):
    print(f"O produto {i} custa R$ {j:.2f}")
2. Adição de Novos Produtos
O programa solicita a entrada de dados para o usuário e adiciona os novos valores no final das listas:

produtos.append(novo_produto)
precos.append(novo_preco)
3. Remoção de Itens
Utiliza o método .pop() para excluir o último elemento inserido, garantindo consistência entre as duas listas:

produtos.pop()
precos.pop()
👤 Autor
Desenvolvido como projeto prático de estudos em Python. ```
