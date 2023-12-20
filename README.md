# CD-EXP-1
# CONVERSION OF NON-DETERMINISTIC FINITE AUTOMATON (NFA) TO DETERMINISTIC FINITE AUTOMATON (DFA)
## AIM
To write a C program for Conversion of Non-Deterministic Finite Automaton (NFA) To Deterministic Finite Automaton (DFA).
## Program:

```
#include <stdio.h>
#include <stdlib.h>
#include <string.h> #define MAX_LEN 100

char NFA_FILE[MAX_LEN];
char buffer[MAX_LEN]; int zz = 0;

// Structure to store DFA states and their
// status ( i.e new entry or already present) struct DFA {
char *states; int count;
} dfa;

int last_index = 0; FILE *fp;

```





