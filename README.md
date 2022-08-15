# Car Engine Audio Database (CEAD)
Dataset with audio files from car engines.

The Car Engine Audio Database (CEAD) consists of ~15-second audio recordings of different car engines from 16 different manufacturers. The manufacturers, models and number of recordings are shown below:

<details><summary>
Database Details
</summary>

Manufacturer  | Model         | Recordings
------------- | ------------- | :----------:
Alpha Romeo   | Giulietta     | 1
BMW           | 116           | 1
&nbsp;        | 520i          | 1
&nbsp;        | x6            | 1
Chevrolett    | Lacetti       | 1
&nbsp;        | Spark         | 3
Citroen       | C3            | 2
&nbsp;        | C4            | 2
&nbsp;        | Saxo          | 2
&nbsp;        | C2            | 1
&nbsp;        | Berlingo      | 1
&nbsp;        | Saxo          | 2
Daewoo        | Matiz         | 1
Fiat          | Panda         | 4
&nbsp;        | Punto         | 3
&nbsp;        | Doblo         | 1
Ford          | Fiesta        | 2
&nbsp;        | Focus         | 3
&nbsp;        | KA            | 1
&nbsp;        | Modeo         | 1
Hyundai       | Atos          | 1
&nbsp;        | i20           | 1
Opel          | Astra         | 6
&nbsp;        | Corsa         | 4
&nbsp;        | Vectra        | 1
Peugeot       | 206           | 2
&nbsp;        | 307           | 3
Renault       | Megane        | 2
&nbsp;        | Twingo        | 2
Seat          | Ibiza         | 1
Skoda         | Octavia       | 1
Suzuki        | Grand Vitara  | 2
Toyota        | Yaris         | 1
VolksWagen    | Polo 1.4      | 1

</details>


The dataset follows the following structure: 
```
.
├── Manufacturer_1
    ├── Model_1
        ├── 1000
            ├── 0001.wav
            ├── 0002.wav
            ...
        ├── 1500
            ├── 0001.wav
            ├── 0002.wav
            ...
        ├── 2000
            ├── 0001.wav
            ├── 0002.wav
            ...
├── Manufacturer_2
    ├── Model_2
    ...
```
Each audio file in each rpm level folder corresponds to the same car, meaning that the 0001.wav in 1000, 1500 and 2000 folders are of the same car.

The  engines  were  recorded  for three different rpm levels (1000, 1500 and 2000 rpm). The reasoning  behind the recording of the  engine  in  different rpm levels is to study if the running speed makes the enginebiometric more discriminative. The sounds of the engines were recorded using an XXL Inside  microphone  from  the  XD02  Drum  Kit  Pack  Micro Microphone   Package,   equipped   with   a   wind   noise reduction  sponge  foam, to  reduce  environmental  noise  as much  as possible. The  microphone  was  connected  to  a smartphone via an XLR Microphone Audio Adapter from SmartRig and the Easy Voice Recorder App was used, with the  following option  settings:

* High sound quality, 
* “.wav”encoding,   
* 44.1KHz   sample   rate   with   noise   and   echo cancellation being enabled. 

To record a sound coming from an engine, the car was left on a neutral gear in all cases and for the cases of 1500 and 2000 rpm, the gas pedal was being pressed so that the engine  was running  steadily at a specific speed.The engines were recorded with the car’s hood being open and by positioning the microphone at thecenterof the engine, for a duration of 15 seconds.

Cite As:

* G. K. Sidiropoulos, G. A. Papakostas, Machine Biometrics - Towards Identifying Machines in a Smart City Environment, IEEE World AI IoT Congress (AIIoT), May 10-13, 2021, Seattle, USA
