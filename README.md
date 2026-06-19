# 📚 Sistema de Biblioteca

> Trabalho final da disciplina de Algoritmos e Programação — UFFS  
> Desenvolvido em Python com execução no Google Colab.

---

## 📋 Descrição

Este projeto foi desenvolvido como trabalho final da disciplina de **Algoritmos e Programação** da **Universidade Federal da Fronteira Sul (UFFS)**. O sistema funciona em modo texto e permite gerenciar uma biblioteca de forma simples e organizada, oferecendo um menu interativo no terminal com as principais operações sobre um acervo de livros.

---

## 🎯 Objetivo do projeto

Colocar em prática os conceitos fundamentais de algoritmos e programação aprendidos ao longo do semestre, desenvolvendo um sistema funcional que simula o gerenciamento de uma biblioteca — desde o cadastro até o controle de empréstimos e devoluções.

---

## ⚙️ Funcionalidades

| Funcionalidade | Descrição |
|----------------|-----------|
| 📖 Cadastro de livros | Adiciona um novo livro ao acervo |
| 🔍 Consulta por código | Localiza um livro pelo seu código único |
| 👤 Consulta por autor | Lista todos os livros de um determinado autor |
| ✏️ Alteração de dados | Edita as informações de um livro cadastrado |
| 🗑️ Remoção de livros | Remove um livro do acervo pelo código |
| 📤 Empréstimo de livros | Registra o empréstimo de um livro disponível |
| 📥 Devolução de livros | Registra a devolução de um livro emprestado |
| 📋 Listagem do acervo | Exibe todos os livros cadastrados no sistema |

---

## 🧠 Conceitos de algoritmos utilizados

O projeto aplica diversos conceitos estudados na disciplina:

- **Listas** — estrutura principal para armazenar o acervo de livros
- **Dicionários** — cada livro é representado como um dicionário com seus atributos
- **Funções** — código modularizado, com cada funcionalidade em sua própria função
- **Estruturas condicionais** — uso de `if/else` para controle de fluxo e validações
- **Estruturas de repetição** — laços `for` e `while` para percorrer e exibir o acervo
- **Tratamento de exceções** — uso de `try/except` para lidar com entradas inválidas
- **Busca sequencial** — algoritmo para localizar livros pelo código, percorrendo a lista elemento por elemento
- **Insertion Sort** — algoritmo de ordenação para manter o acervo organizado alfabeticamente pelo título

---

## 🗂️ Estrutura do livro

Cada livro no sistema é representado por um dicionário com os seguintes campos:

```python
{
    "titulo": "Nome do livro",
    "autor": "Autor",
    "ano": 2025,
    "codigo": "001",
    "status": "disponivel"
}
```

O campo `status` pode assumir os valores `"disponivel"` ou `"emprestado"`, controlando a disponibilidade do livro para empréstimo.

---

## 🚀 Como executar

O projeto foi desenvolvido no **Google Colab** e não requer instalação de dependências.

1. Acesse o notebook pelo link do repositório
2. Abra o arquivo no Google Colab
3. Execute as células em ordem
4. O programa apresentará um **menu interativo no terminal** com todas as opções disponíveis

> Também é possível executar localmente em qualquer ambiente Python 3, copiando o código para um arquivo `.py` e rodando via terminal.

---

## 🛠️ Tecnologias utilizadas

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

---

## 👤 Autor

**Bernardo Melo**  
Estudante de Ciência da Computação — UFFS  
[![GitHub](https://img.shields.io/badge/GitHub-meelober-181717?style=flat-square&logo=github)](https://github.com/meelober)

---

<div align="center">
  <sub>Projeto acadêmico desenvolvido para a disciplina de Algoritmos e Programação — UFFS, 2025.</sub>
</div>
