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
![WhatsApp Image 2025-11-11 at 22 45 09_8a0c2a91](https://github.com/user-attachments/assets/5cf601d1-90c0-4c87-9db0-8b3ee72c97ac)


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
![WhatsApp Image 2025-11-11 at 22 47 16_707c670e](https://github.com/user-attachments/assets/9d6e7e3f-2bea-4e0e-a334-6ddcd75c20ea)

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
