```mermaid

graph TD;
    A[INICIO PROGRAMA] -->
    B{SELECCION OPERACION}
    B -->1=SUMA -->cVALOR_1 --> VALOR_2 --> RESULTADO-->A
    B -->2=RESTA-->VALOR_3 --> VALOR_4 --> RESULTADO-->A
    B-->3=MULTIPLICACION-->VALOR_5 -->VALOR_6-->RESULTADO-->A
    B -->4=DIVISION-->VALOR_7 --> VALOR_8 --> RESULTADO-->A
    B -->5=SALIR -->A
    
```