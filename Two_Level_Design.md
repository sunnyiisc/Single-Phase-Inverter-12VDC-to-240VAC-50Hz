# 1. Design with Ideal elements (Bipolar Square Wave Generation)
We will use a dual voltage type inverter with two switches.

Calucaltions for the design:
![IMG_2509](https://user-images.githubusercontent.com/47363228/226999858-5f1f0c1e-1ea1-4bf1-aefc-5beb22a31a6c.jpg)


### Circuit Diagram:
<img width="1369" alt="Screenshot 2023-03-22 at 21 35 46" src="https://user-images.githubusercontent.com/47363228/226967955-5d1ce540-b54e-4fd3-8221-a524622eb980.png">

### Input and Output Waveforms:
<img width="1248" alt="Screenshot 2023-03-22 at 21 34 02" src="https://user-images.githubusercontent.com/47363228/226968177-11682a54-e073-471a-ae44-4b5cfff72c5d.png">

### Intermediate Net Waveform:
<img width="1310" alt="Screenshot 2023-03-22 at 21 38 15" src="https://user-images.githubusercontent.com/47363228/226968261-c2020e3a-12e0-411d-a8e6-fb413d79653f.png">

-------------------
# 2. Filter Design:
Filtering the Bipolar-Square waveform to get pure 50Hz sine waveform.

Calculation for Filter Design:
![IMG_2511](https://user-images.githubusercontent.com/47363228/227035534-261961aa-63a0-4a49-9992-6187064f23cc.jpg)

Calculation for Filter Implementation:
![IMG_2515](https://user-images.githubusercontent.com/47363228/227035618-c9541153-1422-49bc-979e-70fac0285ad1.jpg)

### Filter Circuit Diagram
Two Cascaded 1st order Low-Pass Filter is used to further supress the higher harmonics.
<img width="1211" alt="Screenshot 2023-03-23 at 01 15 53" src="https://user-images.githubusercontent.com/47363228/227035959-ae981070-7229-4c94-a686-0de90cd2764c.png">

### Input and Output Waveforms:
<img width="1077" alt="Screenshot 2023-03-23 at 01 18 12" src="https://user-images.githubusercontent.com/47363228/227036087-2e070c5a-a154-4db6-b0fd-2c4db3a3bccd.png">

### Input and Output Waveforms with Starting Transient:
<img width="1077" alt="Screenshot 2023-03-23 at 01 17 31" src="https://user-images.githubusercontent.com/47363228/227036195-c9a3da8f-0164-4908-8183-f4e09a0d79cd.png">

---------------------
# 3. Final Inverter Circuit with Filter and Step-Up Transformer (240V 50Hz Sine Wave)
Bipolar-Sqare wave is generated with the dual voltage type inverter. The output is filtered to get 6VAC 50Hz sine wave. A step up transformer with turn ratio 1:40 is used to get the output 240V, 50Hz Single Phase AC Voltage.

### Complete Circuit Diagram:
<img width="1439" alt="Screenshot 2023-03-23 at 01 58 23" src="https://user-images.githubusercontent.com/47363228/227036958-a5955ad5-9095-4c95-84ef-c6ad844d69e0.png">

### Input and Output Waveforms:
<img width="1440" alt="Screenshot 2023-03-23 at 01 59 38" src="https://user-images.githubusercontent.com/47363228/227037069-bfac70e6-4905-4069-a3d8-d212b4cb15f0.png">
