# Lab 1 — GHDL and GTKWave

## Half Adder Example 

**VHDL Entity**

![ha.vhdl](https://github.com/user-attachments/assets/582af3aa-b9be-4462-a00f-2247b5153994)
 
</br>

**Testbench**

![testbench](https://github.com/user-attachments/assets/07ee316e-563f-4bd7-96da-fcad0885747d)

</br>

**Terminal Code**
```
gdhl -a ha.vhdl
ghdl -a ha_tb.vhdl
ghdl -e ha_tb
ghdl -r ha_tb --vcd=ha.vcd 
gtkwave ha.vcd
```

</br>

**Results**

![test1](https://github.com/user-attachments/assets/a96ecd18-028d-42f6-84aa-1d902eb75595)

![test2](https://github.com/user-attachments/assets/265ffcda-b788-4141-a589-c28157a6e840)

![test3](https://github.com/user-attachments/assets/af9945f0-0111-4196-846c-b12529af1665)

![test4](https://github.com/user-attachments/assets/d9e3e816-8052-4ed2-b36b-b106b682ddca)

![test5](https://github.com/user-attachments/assets/5bd9641f-6227-4433-b400-0344f0116dad)
