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

## HOW TO SUBTRACT

![Screenshot 2023-12-09 165007](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/797dcc54-b13c-402c-996f-9575c8e16e30)

![Screenshot 2023-12-09 165018](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/eb26de58-e060-4663-8c65-0999dfb2aa94)

![Screenshot 2023-12-09 165047](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/f72d6eda-3d37-42ce-a382-7dcab34491a0)

![Screenshot 2023-12-09 165054](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/a8765f9e-653f-4f8e-beaa-247bee98a665)

![Screenshot 2023-12-09 165106](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/ee796b36-ee5f-4b55-b67c-f73c6f00d660)

## AND LOGIC

![Screenshot 2023-12-09 171521](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/78d3e121-a85f-449c-a4e5-4ae3d308bf06)

![Screenshot 2023-12-09 171534](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/77a83dc8-395f-4d70-aa64-dd0cb24c32ac)

![Screenshot 2023-12-09 171549](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/e025d74f-8da8-43da-9ce6-28270113cd3c)

## OR LOGIC

![Screenshot 2023-12-09 172255](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/9fa53eea-a0bb-4b5a-b695-440c3177d0db)

![Screenshot 2023-12-09 172305](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/30df6099-779f-434c-b2a8-e5d4bc2165f0)

![Screenshot 2023-12-09 172316](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/65af8467-1bbd-4fab-931a-d6d913d2926a)

## NOT LOGIC 

![Screenshot 2023-12-09 174837](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/bcd71f0a-b984-4422-983b-4d6859154671)

![Screenshot 2023-12-09 174849](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/4639254e-975a-41ab-ad1b-ce8ee19cfda3)

![Screenshot 2023-12-09 174857](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/7bd7e1f6-8966-4440-a20e-3948a3dc8bd7)

## 

![s](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/34140424-e1e6-4637-8d76-fd17ccc28ac1)

![WhatsApp Image 2023-12-14 at 07 47 54_aee1e29d](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/ba37ee47-9630-4be2-ac20-6453b15ae003)

![WhatsApp Image 2023-12-14 at 07 48 20_2880dc33](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/4e8177e1-d148-4f54-9744-3bc90d29ed71)

![WhatsApp Image 2023-12-14 at 07 48 50_ab2ff1ea](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/6445d390-dbfc-4388-ae0f-33bce736890c)

![WhatsApp Image 2023-12-14 at 08 12 00_c5610fb9](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/de73b8eb-0973-45e4-83e1-d8bae7c7c4e8)


![WhatsApp Image 2023-12-14 at 08 12 35_2b73d0e6](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/f2dd48e6-6e16-4296-b5c7-67a3ae08191a)
![WhatsApp Image 2023-12-14 at 08 28 22_2e6a6bf4](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/c1e6d1c6-ac75-4da0-8350-373d11b0f38b)

![WhatsApp Image 2023-12-14 at 08 28 22_d41c9a2d](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/d5092045-a783-4cc2-a803-08f7b8bcd230)

![WhatsApp Image 2023-12-14 at 08 28 22_0f682026](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/7947e822-2501-462d-9ffa-063ae23f16f6)


![WhatsApp Image 2023-12-14 at 08 28 23_149a74d5](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/1e466e36-d725-479e-b27a-83a37a1fd1f0)

![WhatsApp Image 2023-12-14 at 08 28 23_7344e995](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/9fcc479a-3cbc-48fd-be72-a1f0ea58e4c8)

![WhatsApp Image 2023-12-14 at 08 30 11_55bfd847](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/66b8e2db-a6e1-4047-8ccc-52497d873753)

![WhatsApp Image 2023-12-14 at 08 30 11_af028c93](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/bc64daa1-f01c-42b9-841b-4c1116b5c581)

![WhatsApp Image 2023-12-14 at 08 30 12_86dac009](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/23b9ce60-e47b-4bbe-893e-35948e57e61f)



![WhatsApp Image 2023-12-14 at 08 30 12_9cf21d3a](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/70490cbd-c86b-4eac-9c76-bfb71170c76c)


![WhatsApp Image 2023-12-14 at 08 30 12_3b810695](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/20c71e76-2ced-49ad-855c-dca0727b798f)

![WhatsApp Image 2023-12-14 at 08 30 13_9aa133d7](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/9adef52d-d776-4e9a-b1f8-17cc12e051c0)

![WhatsApp Image 2023-12-14 at 08 30 13_72521425](https://github.com/Riyatomar14/cpu-simulator-base-machine-/assets/143107173/b5d5940f-1a1f-4ed1-ad4a-26d5514183cb)




















