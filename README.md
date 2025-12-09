# SEQUENCE_DETECTOR(1001)
## What is this project?
This project detects the binary sequence **1001** from a serial input.  
When the sequence 1001 appears in the input, the output becomes **1**.

This detector is designed as a **Moore Machine** and it supports **overlapping sequences**.

## Purpose of the Project
- To understand how a sequence detector works  
- To learn Finite State Machine (FSM) concepts  
- To design the circuit using **state diagram + state table + logic circuits**  
- To understand how digital systems detect patterns

## How It Works 
The detector checks incoming bits one by one:
1. Look for **1**  
2. If found, look for **0**  
3. Then look for **0** again  
4. Finally look for **1**  
If all four bits appear in order → sequence **1001** is detected → Output = **1**
This is done using:
- **States** 
- **Flip-flops**  
- **Combinational logic**

## What We Designed / Included
- **State diagram**  
- **State table**  
- **Transition table**  
- **K-map simplification**  
- **Flip-flop excitation table**  
- **Final circuit diagram**  
- **Truth table for output**

## Steps in Design
1. Draw the **state diagram** for detecting 1001  
2. Prepare the **state table**  
3. Choose flip-flops (JK / D / T)  
4. Create **excitation table**  
5. Use **K-maps** to simplify boolean equations  
6. Draw the **final circuit**  
7. Test using sample inputs  

## Output Explanation
- **Output = 1** → When the sequence **1001** appears  
- **Output = 0** → Otherwise  
- Overlapping sequences can also be detected 
  
## Example Input
Input: 1 0 0 1 1 0 0 1  
Output: 0 0 0 1 0 0 0 1  

## Note
This project is designed using **digital logic** and **finite state machine (FSM)** concepts.  
