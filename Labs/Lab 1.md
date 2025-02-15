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

![test5](https://github.com/user-attachments/assets/5bd9641f-6227-4433-b400-0344f0116dad)

</br>

## SR Flip Flop Example

**VHDL Entity**

![Screenshot 2025-02-14 210247](https://github.com/user-attachments/assets/06190210-edf8-4d8a-b647-54e0cf33748f)

</br>

**Testbench**

![Screenshot 2025-02-14 210436](https://github.com/user-attachments/assets/c2677331-68ef-4223-a2cc-5100b94ee50f)

</br>

**Terminal Code**
```
gdhl -s SRFF.vhdl SRFF_tb.vhdl
ghdl -a SRFF.vhdl SRFF_tb.vhdl
ghdl -e SRFF_tb
ghdl -r SRFF_tb --vcd=SRFF.vcd 
gtkwave SRFF.vcd
```

</br>

**Results**

![Screenshot 2025-02-14 211434](https://github.com/user-attachments/assets/ee0de70a-3347-4d1a-853d-cd62dc86fe62)
