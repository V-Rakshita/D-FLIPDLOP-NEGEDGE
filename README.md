# D-FLIPDLOP-NEGEDGE

## **AIM:**

To implement  D flipflop using verilog and validating their functionality using their functional tables

## **SOFTWARE REQUIRED:**

Quartus prime

## **THEORY**

## **D Flip-Flop**

D flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, D latch operates with enable signal. That means, the output of D flip-flop is insensitive to the changes in the input, D except for active transition of the clock signal. The circuit diagram of D flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/D-FLIPDLOP-NEGEDGE/assets/154305477/48c81fe8-bc3f-40e7-95e2-519fc155ad51)

This circuit has single input D and two outputs Qtt & Qtt’. The operation of D flip-flop is similar to D Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of D flip-flop.

![image](https://github.com/naavaneetha/D-FLIPDLOP-NEGEDGE/assets/154305477/e5f3fda7-68ec-4a3a-a0a4-cf6f9cc4ab55)

Therefore, D flip-flop always Hold the information, which is available on data input, D of earlier positive transition of clock signal. From the above state table, we can directly write the next state equation as Qt+1t+1 = D

![image](https://github.com/naavaneetha/D-FLIPDLOP-NEGEDGE/assets/154305477/8592c0d8-2917-4142-91b9-d6c30dd891d2)

Next state of D flip-flop is always equal to data input, D for every positive transition of the clock signal. Hence, D flip-flops can be used in registers, shift registers and some of the counters.

## **Procedure**

1.	Open Quartus and go to File -> New Project Wizard to create a new project. 

2.	Then, Go to File -> New -> Verilog HDL File and type the program. Compile and run the program.

3.	Then go to Tools -> NetList Viewers -> RTL Viewer and generate the RTL schematic and save the logic diagram.

4.	Then go to File -> New -> University program VWF. Create nodes for inputs and outputs to generate the timing diagram.

5.	Give different input combinations and go to Run Functional Simulation to generate the timing diagram.

## **PROGRAM**

![Screenshot (355)](https://github.com/user-attachments/assets/5a93b024-ca89-4b1e-8fc1-e379c85cdf2f)


## **LOGIC DIAGRAM AND TRUTH TABLE**
![Screenshot (353)](https://github.com/user-attachments/assets/7d530b06-e209-4ff7-afd8-42917001b58e)

![d](https://github.com/user-attachments/assets/6e2950cb-90d1-4dcc-990d-885285253f64)

## **WAVEFORM**

![Screenshot (354)](https://github.com/user-attachments/assets/8d6d3386-bc5f-45b4-9072-72f71abea991)


## **RESULTS**
Hence D flipflop has been implemented using verilog and their functionality has been validated using their functional tables
