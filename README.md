# 📚 Sistema de Cadastro de Livros (em desenvolvimento)

Este projeto está sendo desenvolvido em **C++** com o objetivo de criar um sistema simples e estruturado para **gerenciar o cadastro de livros**.

O sistema utiliza **Programação Orientada a Objetos (POO)** e organiza os dados através de uma classe `Livraria`, que contém uma estrutura (`struct`) responsável por armazenar as informações de cada livro.

---

## 🧩 Funcionalidades atuais

- Cadastro de um livro via terminal  
- Estrutura de dados (`struct`) para armazenar:
  - Nome do livro  
  - ID do livro  
  - Número de registro  
  - Cor da capa  

---

## 🚧 Funcionalidades futuras (em desenvolvimento)

- Armazenar **vários cadastros de livros** usando `std::vector`  
- Salvar e carregar os dados em **arquivos de texto ou binários**  
- Sistema de **busca e exclusão de livros**  
- Interface de menu interativo no terminal  

---

## ⚙️ Estrutura do projeto

📁 seu_projeto/
├── Livraria.hpp # Cabeçalho da classe Livraria
├── Livraria.cpp # Implementação da classe Livraria
└── main.cpp # Arquivo principal (execução do programa)

yaml
Copiar código

---

## 🖥️ Como compilar

No terminal:

```bash
g++ main.cpp Livraria.cpp -o cadastro
./cadastro
Se estiver usando CLion, basta criar os arquivos no mesmo projeto e rodar o main.cpp.

🧠 Tecnologias
Linguagem: C++17 ou superior

Paradigma: Programação Orientada a Objetos (POO)

Biblioteca padrão: <iostream>, <string>

📅 Status
🚀 Em desenvolvimento ativo.
Novas funcionalidades e melhorias estão sendo adicionadas gradualmente.
