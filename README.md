# Square-Cube-of-a-number-using-8051
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
```asm

MOV A,P0 
MOV R0,A 
MOV B,R0 
MUL AB 
MOV P2,A 
END







```

## OUTPUT

<img width="1600" height="893" alt="WhatsApp Image 2026-06-01 at 7 57 28 AM" src="https://github.com/user-attachments/assets/692b6830-020e-4af1-bbe9-4bf2bc38e9d2" />


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
```asm
MOV A, P0
MOV B, A
MUL AB
MOV R0, A
MOV A, R0
MOV B, P0
MUL AB
MOV P2, A
END








```


## OUTPUT

<img width="2284" height="1132" alt="image" src="https://github.com/user-attachments/assets/0e2fffdc-1e0e-4a37-8cfa-76b68bfce045" />


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


