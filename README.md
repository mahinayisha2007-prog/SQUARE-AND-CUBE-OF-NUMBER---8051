
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

<img width="536" height="324" alt="511744277-a50b3e78-bb39-4728-8950-871c1182b5cc" src="https://github.com/user-attachments/assets/99999b5f-da24-45d2-8af2-11e65944959f" />

![WhatsApp Image 2025-11-16 at 13 36 55_65db438a](https://github.com/user-attachments/assets/9fab98df-a0c1-437e-9fb5-30243116b37e)

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

<img width="439" height="320" alt="511744606-40449533-5a80-445b-84c1-e3461d7cd15b" src="https://github.com/user-attachments/assets/9bc85108-ecf5-4550-a02f-656a02d4be0e" />

![WhatsApp Image 2025-11-16 at 13 38 34_c06a54ef](https://github.com/user-attachments/assets/7658037a-3856-4f42-9d84-cee8a65ec653)

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
