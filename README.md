# WhileCFG
Automating the process of finding leading/trailing set from a simple hardcoded <br />
While loop CFG in C and generating an operator precedence table from the sets <br />
The Context Free grammar taken is <br />
S->w(C)bAe <br />
O->p <br />
C->iOn <br />
C->iOi <br />
A->L;A <br />
A->f <br />
L->i=E <br />
E->T*F <br />
T->i <br />
F->n <br />
<br />S is the start state
<br />w represents 'while' keyword
<br />p represents conditional operators like '==','<=','=>','!='
<br />b represents 'begin'
<br />A represents the statements
<br />e represents the end of the while loop
<br />C represents a condition
<br />i represents an identifier
<br />n represents a constant
<br />L represents an assignment
<br />E represents an operation of an identifier and a constant
<br />This is a very basic implementation in C to give a basic idea

