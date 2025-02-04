# Minimize-the-Cash-Flow
In this project, we explore the application of the Greedy algorithm for optimizing cash flow management. The goal is to minimize the total number of transactions required to settle debts among multiple parties. By implementing this approach in Python, we demonstrate an efficient solution for reducing financial overhead in complex scenarios.

1.Identify Net Cash Flow: Calculate the net amount each person/company owes or is owed by summing up all transactions.

2.Apply Greedy Algorithm: Iteratively settle the maximum possible debt by matching the person with the highest positive cash flow with the person with the highest negative cash flow. 

3.Reduce Transactions: Continue the process until all debts are settled with the minimal number of transactions.


![Project Screenshot](https://github.com/suyash242004/Minimize-the-Cash-Flow/blob/main/image/Eample%20-%201.png?raw=true)


<p align="center"><b>Time Complexity</b></p>


Sorting the debtors and creditors by balance:
Before starting the settlement process, the algorithm typically sorts two lists: one for debtors (those with negative balances) and one for creditors (those with positive balances).
Sorting: O(n log n)

Greedy settlement of debts:
The algorithm iterates over the list of debtors and creditors to settle the minimum balance between each pair.In each iteration, a transaction is performed between one debtor and one creditor, and the balances are updated.
Greedy Settling: O(n)

