
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
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/ac8bf99c-11d3-4533-b0f2-c166d058d35e" />


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
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/8a774588-d417-47e3-8327-d3246c8d43b2" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
