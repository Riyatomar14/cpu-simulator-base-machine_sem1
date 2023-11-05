# cpu-simulator-base-machine-

##  ![Screenshot 2023-11-05 191022](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/216dba24-6895-4251-bc43-0dca5d4e8a7b)

first of all , we have to make 7 register to design a basic machine. The standard register[S], E register[to store carry bit] and I register is 1 bits wide, the pc and ar are 12 bits wide and the other
three registers are 16 bits wide.  
 
![Screenshot 2023-11-05 164725](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/f6033c5e-a346-4019-9c85-0e83d2e8cd08)

then we make two bits, one is conditional bit [store carry bit] by E register and halt bit [to stop] by S register.

![Screenshot 2023-11-05 164739](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/0d5f19d5-a4da-42dd-a84f-39f7b7838815)

a main memory (RAM) consisting of 4096 words, 16 cell size.
![Screenshot 2023-11-05 164749](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/0c0d1509-3e98-4ff8-8231-24c90971a712)

then this type of data is shown on base machine.now next we start to make instruction cycle-

![Screenshot 2023-11-05 164904](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/c42d28f5-d1e8-4339-a15a-af8c07381bd5)

The pc contains the address of the main memory location that contains the next instruction to be executed. 

![Screenshot 2023-11-05 170909](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/85b1afaf-eb81-4e12-b17a-378e5db2dcfc)

In the fetch sequence (the first part of every machine cycle),the next instruction to be executed is copied into the ir.
![Screenshot 2023-11-05 164812](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/58b3ee68-6b05-4295-9924-a599ddb1670d)

then, PC incremented to store the address of next instruction.
![Screenshot 2023-11-05 181931](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/b8bbdc1c-71f4-4215-9a1a-32ae14d58446)

![Screenshot 2023-11-05 164759](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/1e5000ec-5770-4095-8382-1db1d968c7cf)

then instruction is decoded.
![Screenshot 2023-11-05 164821](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/36324d3a-9cf9-45ec-ad7f-0a0bb7b2e7d7)

Then the instruction is executed, which completes the machine cycle. This is followed repeatedly by more machine cycles, each consisting again of the execution of the fetch sequence followed by the execution of a machine instruction
![Screenshot 2023-11-05 164852](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/02c8e331-200b-46e0-b88f-cbfb2021d0cb)

![Screenshot 2023-11-05 164835](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/a04185cf-dd11-4d62-936b-cbd20fb2f987)

![Screenshot 2023-11-05 164919](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/fd23f47a-b24b-49a4-be25-35522c6bc5dd)



