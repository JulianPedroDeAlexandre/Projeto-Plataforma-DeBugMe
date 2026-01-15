# Plataforma DeBugMe 

Este repositório reúne os projetos e exercícios da **Plataforma DeBugMe**, organizados em páginas numeradas de **01 a 15**. Cada página apresenta um objetivo claro, materiais de apoio e instruções práticas para construir e entender soluções em **HTML, CSS e JavaScript**.

--- 

## Estrutura do Projeto 

### Arquitetura 

- Cada exercício está em um arquivo HTML separado (`projeto1.html` até `projeto15.html`). 
- Isso permite que cada página seja independente, mas siga uma mesma identidade visual e lógica de navegação. 

### Componentes comuns 

- **Cabeçalho** com título e botões de navegação. 
- **Área central** com o conteúdo do exercício (explicação + código + prática). 
- **Rodapé** com links para avançar ou voltar entre páginas. 

--- 

## Troca de Páginas 
- **Botões numerados:** No topo e rodapé há uma sequência de botões (1 a 15). Cada botão leva diretamente ao exercício correspondente (`projetoX.html`). 

- **Botões de navegação rápida:** Além dos números, há botões de **“Voltar”** e **“Avançar”** que permitem seguir a ordem sugerida sem precisar voltar ao índice. 

---

 ## Tema Dark/Light 

 - **Alternância de tema:** 
 Implementada com `classList.toggle('modewhite')` no elemento `<body>`.

- **Tema padrão:** escuro. 
- **Tema alternativo:** claro (ativado ao clicar no botão de tema). 

Marcação do Exercício
Botões de seleção:  
Cada exercício tem um botão que pode ser marcado para indicar conclusão.
Ao clicar, o botão muda de estilo (ex.: cor diferente ou ícone de check).

Persistência opcional:  
Em alguns exercícios mais avançados (como o Relógio de Ponto), há uso de localStorage.
Esse mesmo recurso pode ser usado para salvar quais exercícios já foram marcados como concluídos, mesmo após recarregar a página.

Funcionalidades Extras
Explicação + prática:  
Cada página traz uma explicação teórica e logo abaixo o código para testar.

Consistência visual:  
Todos os exercícios compartilham o mesmo layout, o que facilita a navegação e dá a sensação de plataforma única.

Visão Geral dos Projetos (1–15)
Projeto 1 — Introdução ao DOM
Objetivo: primeiros passos com HTML e manipulação básica de elementos.

Conceitos: estrutura HTML, getElementById, innerText, uso de eventos de clique com função normal, com addEventListener e com addEventListener usando arrow function.

Desafio: comparar os três tipos de função e entender suas diferenças na prática.

Projeto 2 — Simulação de Cadastro e Login
Objetivo: cadastrar nome e idade e validar login comparando com dados salvos.

Conceitos: getElementById, .value, .innerText, onclick, if/else.

Desafio: substituir onclick por addEventListener com arrow functions.

Projeto 3 — Calculadora
Objetivo: criar calculadora funcional.

Conceitos: eventos de clique, variáveis globais, funções para cada botão, uso de eval() para calcular expressões.

Desafio: refatorar para reduzir repetição de código.

Projeto 4 — Cadastro de Pessoas com createElement
Objetivo: CRUD simples em tabela usando criação e remoção de elementos.

Conceitos: createElement, appendChild, deleteRow, loops for, if.

Desafio: implementar edição de registros além da exclusão.

Projeto 5 — Cálculo de CPF
Objetivo: calcular dígitos verificadores de um CPF.

Conceitos: split, for, multiplicação por pesos, join, slice, template literals.

Desafio: validar CPF completo e mostrar mensagens de erro.

Projeto 6 — Carrossel
Objetivo: criar carrossel de imagens funcional.

Conceitos: querySelectorAll, forEach, addEventListener('click'), classList.add/remove.

Desafio: adicionar autoplay com setInterval.

Projeto 7 — Card Pessoal
Objetivo: criar card com dados pessoais e ícones interativos.

Conceitos: Flexbox, ícones com boxicons, mouseenter, innerText, integração com API randomuser.me..

Desafio: permitir atualização automática dos dados via API.

Projeto 8 — Pokédex API
Objetivo: consumir PokeAPI e exibir pokémons em cards.

Conceitos: fetch, async/await, for...of, map, join, appendChild.

Desafio: implementar busca por nome ou número do pokémon.

Projeto 9 — Calculadora Refatorada
Objetivo: melhorar código da calculadora anterior.

Conceitos: querySelectorAll, forEach, addEventListener, arrow functions, refatoração para menos linhas.

Desafio: adicionar histórico de cálculos.

Projeto 10 — Cadastro de Pessoas com Objetos
Objetivo: cadastrar pessoas e exibir em cards.

Conceitos: objetos literais, arrays, push, forEach, preventDefault, reset.

Desafio: implementar exclusão e edição de pessoas cadastradas.

Projeto 11 — Clicker (Jogo de cliques)
Objetivo: ganhar moedas clicando e comprar upgrades.

Conceitos: querySelector, addEventListener, setInterval, variáveis de estado.

Desafio: implementar upgrades adicionais com custos crescentes e placares.

Projeto 12 — Carrossel X-Men
Objetivo: trocar imagem e descrição ao passar mouse sobre personagens.

Conceitos: querySelectorAll, mouseenter, classList.

Desafio: adicionar novos personagens e animações de transição.

Projeto 13 — Git/GitHub
Objetivo: aprender versionamento e comandos básicos.

Conceitos: git init, git add, git commit, git push.

Desafio: versionar um projeto completo e criar branches.

Projeto 14 — Alternância de Tema
Objetivo: alternar entre tema claro e escuro.

Conceitos: classList.toggle, CSS escopado.

Desafio: aplicar alternância de tema em três projetos diferentes.

Projeto 15 — Relógio de Ponto
Objetivo: registrar horários e salvar no localStorage.

Conceitos: classe Ponto, JSON.stringify/parse, loops forEach e for...in.

Desafio: formatar registros, evitar duplicações e permitir exportação dos dados.

Créditos
Autor: Julian Pedro De Alexandre

Ano: 2025
Ultima atualização: 2026

Fonte: Plataforma DeBugMe