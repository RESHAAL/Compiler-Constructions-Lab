# Experiment 9: Desk calculator with error recovery

## Terminal Session

```bash
lab-03-15@lab-03-15-OptiPlex-3280-AIO:~\$ gedit file-288.y
lab-03-15@lab-03-15-OptiPlex-3280-AIO:~\$ gedit file-288.l
lab-03-15@lab-03-15-OptiPlex-3280-AIO:~\$ yacc -d file-288.y
lab-03-15@lab-03-15-OptiPlex-3280-AIO:~\$ lex file-288.l
lab-03-15@lab-03-15-OptiPlex-3280-AIO:~\$ gcc lex.yy.c y.tab.c -lfl
lab-03-15@lab-03-15-OptiPlex-3280-AIO:~\$ ./a.out
Desk Calculator: Enter expressions (Ctrl+C to exit)
2+2
Result = 4
4+(3*8)
Result = 28
98-48
Result = 50
44*8
Result = 352
762/3
Result = 254
```
