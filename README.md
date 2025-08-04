# Calculadora de Petshop 🐶🐱

Este é um sistema web simples que simula a escolha do melhor petshop com base na distância e nos preços cobrados para banho de cães pequenos e grandes, considerando se é um dia de semana ou fim de semana.

## Como executar o sistema

1. Clone o repositório ou baixe os arquivos.
2. Abra o arquivo `calculadoraPet.html` em qualquer navegador moderno.
3. Preencha as informações no formulário e clique em **"Calcular melhor petshop"**.
4. O resultado será exibido na tela com o nome do petshop mais vantajoso e o valor total.

## Premissas assumidas

- Todos os petshops estão disponíveis todos os dias.
- A escolha considera apenas o menor custo total; em caso de empate, o mais próximo é selecionado.
- A entrada de dados é sempre válida (usuário sempre preenche corretamente).
- O sistema não considera horários, apenas o tipo de dia (semana ou fim de semana).

## Decisões do projeto

- A aplicação foi desenvolvida utilizando apenas **HTML**, **CSS** e **JavaScript puro**, sem frameworks.
- A lógica de negócios (cálculo dos preços e comparação) foi feita toda em JavaScript, no próprio arquivo HTML para facilitar a execução e visualização.
- A interface foi mantida simples e funcional para priorizar a lógica e o entendimento.

## Exemplo de uso

Suponha que hoje seja um **fim de semana**, você tem **1 cachorro pequeno** e **2 grandes**.

- Você preencherá:
  - Dia da semana: `Fim de semana`
  - Quantidade de cães pequenos: `1`
  - Quantidade de cães grandes: `2`

Clique em **Calcular melhor petshop**.

O sistema irá exibir, por exemplo:
> **Melhor opção: Meu Canino Feliz**  
> **Valor total: R$ 120,00**

*(Esse valor varia de acordo com os dados e a lógica definida no script.)*

---

🧑‍💻 Desenvolvido por Luan Guimarães
