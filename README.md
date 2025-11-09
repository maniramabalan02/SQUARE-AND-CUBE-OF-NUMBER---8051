  
# SQUARE AND CUBE OF A NUMBER
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
ORG 0000H
MOV A, P0
MOV R0, A
MOV B, R0
MUL AB
MOV P2, A
SJMP $
END
```

## OUTPUT

![fb2b311167cb46aba43e26beebbabc9e 1](https://github.com/user-attachments/assets/f18f2ec7-54ef-4d7d-9f3b-b16dd8e4b5e9)

## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
ORG 0000H
MOV A, P0
MOV B, A
MUL AB
MOV R0, P0
MOV B, R0
MUL AB
MOV P2, A
SJMP $
END
```

## OUTPUT

![47e90ec4df4c4fc88ecaf93612423ee2 1](https://github.com/user-attachments/assets/bfb9f5d6-1ce3-416f-8eff-0023e8fea9a4)

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
