# Título Questões - Transações

1. SImular uma conta bancária id, titular e saldo poitivo.
2. ana: 1000, Bruno: 500, Carlos: 300, Daniela: 800.
3. O saldo correspondente ao id 1 recebeu + 100 e o id 2 -100.
4. Para evitar problemas de concorrrência, caso fossem duas transações, uma com cada update, poderia haver uma falha.
5. Porque houve um rollback, logo, a transação foi completamente apagada.
6. Em situações onde existe a possibilidade de concorrência, e por consequência, suerge a possibilidade de erros como a leitura suja.
7. Para evitar o erro de saldo negativo.
8. Um erro de exceção local, já que uma regra de negócio foi violada.
9. A conta de id 4 foi debitada e as contas de id 1 e 2 foram creditadas.
10. Pela mesma ideia de evitar concorrências
11. Verificar se os dados estariam atualizados ou se teriam sido alterados.
12. Uma transação não sabe nada sobre a outra, e antes de um commit, a transação não está concluída.
13. A sessão 2 esperou até que a sessão 1 fosse finalizada para executar.
14. Porque jáhavia uma transação sendo executada na mesma conexão.
15. usado para bloquear as linhas retornadas, impedindo que outras transações as modifiquem ou bloqueiem até que a transação atual seja concluída.
16. Porque estão lidando com registros diferentes, a sessão 1 usa o id 1 e a sessão 2 usa o id 4.
17. Quando a mesma operação é feita em linhas diferentes da tabela, não há concorrência operacional.
18. Saber dados referentes às transações é importante para monitorar e corrigir possíveis erros.
19. Para garantir que a movimentação esteja com dados coerentes com as mudanças feitas nos updates
20. Occorreira um tipo de leitura suja, pois os dados estariam desconexos.
21. Garanntiu que os updates feitos dentro da transação não fossem aplicados.
22. Precisa expliar porra?
23. 

