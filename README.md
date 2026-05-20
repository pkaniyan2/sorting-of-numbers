# sorting-of-numbers
## Aim
To write and execute an Assembly Language Program for sorting data in Ascending and  descending order using 8051 microcontroller on Keil software.
---

## Apparatus Required
- Personal Computer  
- Keil µVision software  
---

## Algorithm(ASCENDING ORDER)
1. Initialize the register **R7** with count (number of elements).  
2. Get the first two elements into two registers.  
3. Compare the two elements:  
   - If the value in register **R0** is lower, exchange **A** and **R0** data.  
   - Otherwise, increment pointer and decrement register **R7**.  
4. Check if **R7 = 0** → if yes, move the register **R0 & A**.  
5. Increment pointer and decrement **R7**.  
6. If **R7 ≠ 0**, repeat from Step 2.  
7. Otherwise, stop the program.  
---

## Program (Ascending order)

```asm




```
## OUTPUT(Ascending order)<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/1f0c99ad-c10b-4f02-b8f4-be7c40776bc5" />

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/104354d3-742a-4d50-9953-923221c58d78" />


---

## Algorithm(Descending order)
1. Initialize the register **R7** with count.  
2. Get first two elements in two registers.  
3. Compare the two elements of data:  
   - If the value of **R0** register is high, then exchange **A** and **R0** data.  
   - Else, increment pointer and decrement register **R7**.  
4. Check if **R7 = 0**, then move the contents of **R0** and **A**.  
5. Again increment pointer and decrement **R7**.  
6. Check if **R7 = 0**:  
   - If **No**, repeat the process from Step 2.  
   - If **Yes**, stop the program.  
---
## Program (Descending order)

```asm




```
## OUTPUT(Descending order)<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/1f0c99ad-c10b-4f02-b8f4-be7c40776bc5" />




---
## RESULT:
Thus the sorting of given data was done using 8051 keil software.

