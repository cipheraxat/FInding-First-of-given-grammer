# FInding-First-of-given-grammer

Epsilon is represented by @ and terminals with only single characters work, example a terminal as 'id' won't work here

Input

Enter no. of terminals: 5
Enter the terminals :
+
*
a
(
)
Enter no. of non terminals: 5
Enter the non terminals :
E
B
T
Y
F
Enter the starting symbol: E
Enter no of productions: 5
Enter the productions:
E->TB
B->+TB/@
T->FY
Y->*FY/@
F->a/(E)


output


   Non Terminals           First        
         E               {'(', 'a'}     
         B               {'+', '@'}     
         T               {'(', 'a'}     
         Y               {'*', '@'}     
         F               {'(', 'a'}
