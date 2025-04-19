# HF Noise Canceller

This project was born out of necessity for my day-to-day activities as a ham radio operator. The QRM is becoming more intense every day, with current levels reaching S9, so I needed to find a way to reduce it.  
This device is still in the design phase, which is why there is still little information in the repository. As I continue to develop it, I will add more details.

#### Note: The circuit has not yet been tested.

The original design is based on an article for building a noise canceller by colleague EA1KO, with some modifications that presumably could improve its performance, such as:

1. The incorporation of signal relays instead of extending the RF cables to the switches. This ensures that the wiring is entirely DC, with no RF signals. Due to these relays, the wiring is simplified.

2. The addition of a 1.2 MHz high-pass filter at the input of the auxiliary antenna. The use of this filter can be selected or bypassed via a switch.

3. PTT input from the transceiver to switch the canceller to transmit mode (in this mode, the power relay creates a bypass between the main antenna and the transceiver). The automatic switching when RF is detected is only as a safety measure.

4. LA1, LA2, and LA3 are 12V bulbs used to protect sensitive circuits from RF power when the equipment is in transmission mode.

5. The addition of shielding in the first stage of noise amplification, to prevent noise that does not come from the auxiliary antenna.

![Noise Canceller 2 0_t](https://github.com/user-attachments/assets/b486abe7-adf7-47c5-9f1a-07e7165e1199)
_Top view of the 3D model._

![Noise Canceller 2 0_bot](https://github.com/user-attachments/assets/756db7bb-3946-4b37-99b8-ee39da5b0230)
_Bottom view of the 3D model._

### Additional information for assembly:  

1. Once the SMD and THT components are mounted on the PCB, the jumpers marked from JP1 to JP6 need to be short-circuited. These jumpers are a very effective method to determine where the ground connections and power supply positives are linked across the entire PCB.

2. A 50-ohm coaxial cable needs to be placed to connect TP15 and TP13 with TP14 and TP12, respectively. I have preferred this connection to be made using an external cable rather than a copper trace to avoid possible interference (EMI).

3. All cables going to connectors and switches must be connected to the corresponding TPn, according to the schematic.


![Captura de pantalla 2025-04-17 a las 23 23 01](https://github.com/user-attachments/assets/1a49ffe5-d395-461c-a5b6-a19b20405de1)

_PCB Top side._

![Captura de pantalla 2025-04-17 a las 23 24 20](https://github.com/user-attachments/assets/e434a091-9910-40a2-8e50-645857a5ab62)

_PCB Bottom side._

### Transformers
![WhatsApp Image 2025-04-19 at 18 45 04](https://github.com/user-attachments/assets/e37ef704-57c1-4b17-8f37-3a4fe8dd0ff3)
_Detail of each transformer._



![Top view](https://github.com/user-attachments/assets/2d5949b0-e422-4094-8667-19631c2b7dad)
_3D model top view._

![Vista frontal](https://github.com/user-attachments/assets/c245ac68-4a6e-4d55-a854-13174ce48cfc)
_3D model front view._

![Vista posterior](https://github.com/user-attachments/assets/3474e85c-5287-4a3d-beca-17526e29907a)
_3D model rear view._

![WhatsApp Image 2025-04-19 at 12 38 03 (1)](https://github.com/user-attachments/assets/429607b1-1403-4ede-8dad-e9d45be53317)
_Printed 3D prototype._

![WhatsApp Image 2025-04-19 at 12 38 03](https://github.com/user-attachments/assets/da657c5f-2422-41de-9493-b453be430c18)
_Printed 3D prototype._

![WhatsApp Image 2025-04-19 at 12 46 19](https://github.com/user-attachments/assets/e1356482-de30-4050-a8a0-3755f47c0f55)
_Printed 3D potentiometer extender._

