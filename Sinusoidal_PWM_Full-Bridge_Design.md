# 1. Design for generation of the PWM sequence:
Generating the PWM singal for Full-Bridge type inverter.

Calucaltions for the design:
![IMG_2556](https://user-images.githubusercontent.com/47363228/228323982-e2d9a1c4-0e25-4c14-8006-fe69476274f4.jpg)

![IMG_2558](https://user-images.githubusercontent.com/47363228/228324015-9f9496e0-9c8e-4e5e-a7af-5bc44aca722f.jpg)

### Circuit Diagram:
<img width="1261" alt="image" src="https://user-images.githubusercontent.com/47363228/228352333-384c37b1-520e-49db-8a79-2081e9c767a5.png">


### Input Triangular, Pilot Sine and Output PWM, filtered PWM Waveforms:
<img width="946" alt="image" src="https://user-images.githubusercontent.com/47363228/228352628-0c7a94d4-69b1-4683-93c9-20c93e5c675d.png">


### Fourier Transform of the PWM and filtered output waveform:
<img width="878" alt="image" src="https://user-images.githubusercontent.com/47363228/228352762-ba823a42-f354-44f5-aba3-c609b2ba68e9.png">



# 2. Design with Ideal elements (Sinusoidal PWM)
We will use a dual voltage type inverter with four switches Full Bridge Configuration. The controlling singal will be sinusoidal PWM.

Calucaltions for the design:
![IMG_2562](https://user-images.githubusercontent.com/47363228/228578696-99ae8e60-86ae-4b89-8f2a-c63d3902f39a.jpg)


### Circuit Diagram:
<img width="1280" alt="image" src="https://user-images.githubusercontent.com/47363228/228625738-e9017f3c-7b81-4b41-9859-fa7d68a052de.png">


### PWM Switching generation and switching control Waveforms:
<img width="1018" alt="image" src="https://user-images.githubusercontent.com/47363228/228625913-ec720b88-c7e8-4a9e-aea1-1b70da5bf408.png">


### PWM Switching and Output Waveforms:
<img width="1018" alt="image" src="https://user-images.githubusercontent.com/47363228/228626196-625fd70a-5589-4cd5-a589-aacac67ee7e3.png">


### Fourier Transform of the output waveform:
<img width="952" alt="image" src="https://user-images.githubusercontent.com/47363228/228626312-7869fdf6-9f29-4dba-9740-6958ecf99d70.png">
