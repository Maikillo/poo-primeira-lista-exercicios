# POO - Primeira Lista de Exercícios
**Aluno:** Marcos Vinicios Gonçalves Mendes
---
## Questão 1
Resposta: B

A resposta é a letra B, pois mesmo que a palavra public seja uma palavra reservado do java ela esta em maiúsculo nas opções e pode sim ser um identificador java válido. Ela segue as devidas regras como para ser uma variável deve se começar com letra(no caso do Public ela deve ser maiúscula pois com o "p" wm minúsculo já é considerado uma palavra reservado do sistema java) e  não pode conter caracteres especial a não ser o _ (underline).

## Questão 2
Resposta: C

byte x = 5;                            
byte y = 10;
"int" z = x + y;

## Questão 3
Resposta: A

int x = 5 * 4 % 3                       
- A expressão é realizada com prioridade pela multplicação e em seguida pela divisão. Assim a resolução da expressão fica 5 * 4 = 20 e seu resultado é usado para completar a resolução da  expressão 20 % 3 = 2, pois o operado "%" pega o resto da operação matemática.
                                                                                                                         
System.out.println(x);                 
- Aqui é imprimido o valor da operação que esta armazenada na variável x.                                               

## Questão 4
Resposta: C

int c = 7;   
- O valor da variável c = 7                            
int result = 4;

- O valor da variável result = 4
result += ++c;

- Aqui o a variável c é incrementada e agora passa a ter o valor de 8 e é somado com o a variável result q obtem o valor 4.                                                                       
System.out.println(result);             - Aqui é imprimido o valor da operação que esta armazenada na variável result.                                                 
