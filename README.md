# anotacoes-em-Java

## Problema Proposto

1. Você deve completar a anotação personalizada @FamilyBudget e a classe FamilyMember.
2. A anotação será usada para restringir métodos com base no papel do usuário (userRole) e nos limites de orçamento.
3. Com base na entrada fornecida, o programa:
   - Identifica o método correto a ser chamado (por exemplo, seniorMember ou juniorUser) usando a anotação.
   - Verifica se o gasto (money spent) está dentro do orçamento permitido.
   - Executa o método correspondente ou imprime "Budget Limit Over" se o gasto exceder o orçamento.

## Formato de Entrada
1. A primeira linha contém um número inteiro T (quantidade de casos de teste).
2. Cada caso de teste contém:
   - Uma string representando o papel do usuário (UserRole) — SENIOR ou JUNIOR.
