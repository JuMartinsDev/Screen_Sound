# Screen Sound

Screen Sound é uma aplicação de console em C# que permite o cadastro, avaliação e consulta de bandas musicais. O usuário pode registrar bandas, atribuir notas a elas e visualizar a média dessas avaliações.

---

## Funcionalidades

- Registrar novas bandas.
- Listar todas as bandas cadastradas.
- Avaliar uma banda adicionando uma nota.
- Exibir a média das notas de uma banda específica.
- Interface amigável com logo em ASCII e mensagens de boas-vindas.

---

## Como usar

1. Execute o programa.
2. Escolha uma das opções do menu digitando o número correspondente:
   - `1` para registrar uma banda.
   - `2` para mostrar todas as bandas cadastradas.
   - `3` para avaliar uma banda.
   - `4` para exibir a média de notas de uma banda.
   - `-1` para sair do programa.
3. Siga as instruções exibidas no console.

---

## Tecnologias utilizadas

- Linguagem: C#
- Plataforma: .NET (Console Application)

---

## Detalhes do código

- Utiliza um `Dictionary<string, List<int>>` para armazenar as bandas e suas avaliações.
- Implementa tratamento simples para opções inválidas do menu.
- Calcula a média das notas usando o método LINQ `Average()`.
- Exibe um logo em ASCII no início da aplicação para uma melhor experiência visual.

---

## Sobre

Aplicação console em C# com .NET que simula o backend de um sistema de cadastro e avaliação de bandas. Projeto focado em prática de lógica, coleções (`List` e `Dictionary`), estruturação por métodos e princípios de clean code.
