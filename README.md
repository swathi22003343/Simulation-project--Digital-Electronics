# DESIGN AND SIMULATE THE LOGIC DIAGRAM USING VERILOG
# AIM:
To Design and simulate the logic diagram using Verilog.

# EQUIPMENTS REQUIRED:
Hardware – PCs, Cyclone II , USB flasher.

Software – Quartus prime.

# PROCEDURE:
Step 1:
Create module encoder and decoder.

Step 2:
Get inputs and outputs for encoders and decoders.

Step 3:
perform or operation for encoder and and logic for decoders.

Step 4:
perform RTL LOGIC and get waveform.

Step 5:
End the module.

# LOGIC DIAGRAM:
![image](https://github.com/swathi22003343/Simulation-project--Digital-Electronics/assets/120440439/449712de-ad82-4e0b-89e2-fb93e3bf7c04)

# NETLIST DIAGRAM:
![image](https://github.com/swathi22003343/Simulation-project--Digital-Electronics/assets/120440439/7b8a5154-84f4-438f-a99f-fd5b70ab982e)

# TIMING DIAGRAM:
![image](https://github.com/swathi22003343/Simulation-project--Digital-Electronics/assets/120440439/838e3266-6986-4b6f-8538-f3318381ddd8)

# TRUTH TABLE :
![image](https://github.com/swathi22003343/Simulation-project--Digital-Electronics/assets/120440439/677124da-0022-44cd-8758-203943afe112)

# PROGRAM:
```
Program to To Design and simulate the logic diagram using Verilog.
Developed by: SWATHI D
RegisterNumber: 212222230154
```
```
module e13(x,y1,y2,z1,z2):
Input x,y1,y2;
Output z1,z2;
Assign z1=(x&y) | ((~x) & y2);
Assign z2=((~x)&y2) | (x&(~y1));
endmodule
```

# RESULT:
Thus the program to design and simulate the logic diagram using Verilog.



