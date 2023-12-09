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

## how to add

![Screenshot 2023-12-09 162653](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/63a19c9b-d3da-4b47-a259-8c5e88c2a932)

![Screenshot 2023-12-09 162713](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/f0e491ac-2725-4221-b027-25a9be66bed6)

![Screenshot 2023-12-09 162720](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/4b395005-d920-4af1-920e-2a1c9a5621c6)

![Screenshot 2023-12-09 162731](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/af6c033f-1d52-4e22-8a92-eaad2e4176e1)

![Screenshot 2023-12-09 162741](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/8dd7974e-83d5-40fb-afc5-a1b534b72505)

![Screenshot 2023-12-09 162749](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/cf321d0f-ac56-4f88-9a32-1a52c265f140)

![Screenshot 2023-12-09 162759](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/b9f5d80e-4c4a-46fc-90ee-db4c03210e74)

![Screenshot 2023-12-09 162826](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/4e95d628-389c-40cc-b08c-cc144d398991)

![Screenshot 2023-12-09 162844](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/f5f076fb-ae76-4728-94e3-c382376b0259)

![Screenshot 2023-12-09 162908](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/3d65d3b3-6996-402a-8327-f79f1687a8a1)

![Screenshot 2023-12-09 162927](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/788c314d-7f72-4632-baa3-c71403aaf0b5)

![Screenshot 2023-12-09 162936](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/14930bfb-e542-4a2b-a453-dfad3760ce81)

## HOW TO SUBTRACTION

![Screenshot 2023-12-09 165007](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/797dcc54-b13c-402c-996f-9575c8e16e30)

![Screenshot 2023-12-09 165018](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/eb26de58-e060-4663-8c65-0999dfb2aa94)

![Screenshot 2023-12-09 165047](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/f72d6eda-3d37-42ce-a382-7dcab34491a0)

![Screenshot 2023-12-09 165054](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/a8765f9e-653f-4f8e-beaa-247bee98a665)

![Screenshot 2023-12-09 165106](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/ee796b36-ee5f-4b55-b67c-f73c6f00d660)









