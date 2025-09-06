# Exercise 3: Flow Sequence or Flow Chart using Repeat, While and Do-While Loops  

---
#### Name: Malar Mariam S
#### Reg no: 212223230118

## Part A: Repeat (Using Assign + While)

### Aim  
To demonstrate how to use a **While loop** in UiPath to repeat actions until a condition is no longer true.  

### Procedure  
1. Open **UiPath Studio** → Create a new process → Name it **LoopingDemo**.  
2. Create **"PartA.xaml"**.  
3. Drag a **Sequence** activity into the main panel.  
4. Declare variables:  
   - `counter` → Int32 → Default = `1`  
   - `limit` → Int32 → Default = `5`  
5. Add an **Assign** activity: `counter = 1`  
6. Add a **While** activity with condition: `counter <= limit`  
7. Inside the While loop:  
   - Add **Message Box** → `"Count: " + counter.ToString`  
   - Add **Assign** → `counter = counter + 1`  
8. After the loop, add a final **Message Box** → `"Loop ended"`.  

### Output  

<img width="1919" height="1017" alt="image" src="https://github.com/user-attachments/assets/67902466-4c27-4b16-a62b-8dd209df35da" />
<img width="1919" height="1019" alt="image" src="https://github.com/user-attachments/assets/3d3b6b34-2f7a-48ed-b9a5-7f9fe479fa0b" />
<img width="1919" height="1021" alt="image" src="https://github.com/user-attachments/assets/3b62fa4a-dcc0-4bbe-ad8f-f8abf68a0754" />
<img width="1919" height="1015" alt="image" src="https://github.com/user-attachments/assets/b191c6b9-fc80-4c6f-8914-7fc05f4c1ede" />
<img width="1919" height="1019" alt="image" src="https://github.com/user-attachments/assets/311b4cf8-76b8-4a7b-8245-4b3dbf16a403" />
<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/bc103645-d18c-47e1-8c9a-f602a4e825d2" />


## Part B: Do-While Example  

### Aim  
To demonstrate the **Do-While loop** in UiPath, which executes its block at least once before checking the condition.  

### Procedure  
1. Create a new workflow file (e.g., `PartB.xaml`).  
2. Declare variable:  
   - `firstRun` → Boolean → Default = `True`  
3. Drag a **Do While** activity into the panel.  
4. Inside the Do While:  
   - Add **Message Box** → `"This block runs at least once"`  
   - Add **Assign** → `firstRun = False`  
5. Set Do While condition → `firstRun = True`.  

### Output  

<img width="1919" height="1017" alt="image" src="https://github.com/user-attachments/assets/f162273b-fc9c-4457-9f6c-df6b799015e0" />

### Result

The program was executed successfully, demonstrating the working of While and Do-While loop.
