# WhileCFG
Automating the process of finding leading/trailing set from a simple hardcoded While loop CFG in C and generating an operator precedence table from the sets
The Context Free grammar taken is
S->w(C)bAe
O->p
C->iOn
C->iOi
A->L;A
A->f
L->i=E
E->T*F
T->i
F->n
S is the start state
w represents 'while' keyword
p represents conditional operators like '==','<=','=>','!='
b represents 'begin'
A represents the statements
e represents the end of the while loop
C represents a condition
i represents an identifier
n represents a constant
L represents an assignment
E represents an operation of an identifier and a constant

This is a very basic implementation in C to give a basic idea

