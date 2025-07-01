# 🚗 Sistema de Cadastro e Relatório de Carros

Este é um projeto simples em HTML, CSS e JavaScript utilizando jQuery, desenvolvido como Trabalho Final da disciplina de Desenvolvimento Web. O sistema permite o cadastro, alteração, exclusão, listagem, busca e filtragem de carros com persistência local via `localStorage`.

---

## 📌 Funcionalidades

### Página de Cadastro (`cadastro.html`):
- Inserir novo carro
- Alterar carro (usando o Renavam como chave)
- Excluir carro (com confirmação)
- Validação de:
  - Placa obrigatória
  - Preço maior que zero
- Atributos cadastrados:
  - Renavam
  - Marca
  - Modelo
  - Placa
  - Cor
  - Preço

### Página de Relatório (`relatorio.html`):
- Listar todos os carros cadastrados
- Buscar carro pelo Renavam
- Filtrar carros por:
  - Marca
  - Modelo
  - Cor
- Calcular e exibir a média de preços dos carros cadastrados

---

## 🛠 Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (JS)
- jQuery
- `localStorage` para armazenamento dos dados

---

## 💾 Como Usar

1. Abra o arquivo `cadastro.html` em um navegador moderno.
2. Cadastre um ou mais carros.
3. Clique em "Ir para Relatório" para visualizar, filtrar ou buscar os registros.

---

## 📁 Estrutura dos Arquivos

├── cadastro.html

├── relatorio.html

├── style.css

└── README.md

---

## 🧑‍🎓 Objetivo do Projeto

Este projeto foi desenvolvido com foco na prática de:
- Manipulação do DOM com jQuery
- Uso de `localStorage` para persistência de dados entre páginas
- Operações com vetores de objetos e funções de array (`filter`, `find`, `reduce`, etc.)

---