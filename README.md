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
   - Um número inteiro indicando a quantia gasta (MoneySpend).

### Exemplo de entrada:

```
3
SENIOR 75
JUNIOR 45
SENIOR 40

```

### Formato de Saída
Para cada caso de teste:

- Imprima informações sobre o papel do usuário (Senior Member ou Junior Member), o valor gasto, e o orçamento restante.
- Caso o gasto exceda o limite, imprima: Budget Limit Over.

### Exemplo de saída:

```
Senior Member
Spend: 75
Budget Left: 25

Junior Member
Spend: 45
Budget Left: 5

Senior Member
Spend: 40
Budget Left: 60

```

### O que Implementar
1. Anotação @FamilyBudget:
   - Definir o atributo userRole para identificar o papel do usuário.
   - Adicionar outro atributo chamado budgetLimit para definir o limite de orçamento.
  
2. Classe FamilyMember:
   - Completar os métodos seniorMember e juniorUser.
   - Adicionar a anotação @FamilyBudget aos métodos e configurar o limite de orçamento.
