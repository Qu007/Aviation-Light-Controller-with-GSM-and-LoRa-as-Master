# Aviation-Light-Controller-with-GSM-and-LoRa-as-Master

# Overview 
Industrial wireless controller designed for remote monitoring and control in distributed field 
systems. The board integrates long-range RF communication with cellular backhaul, onboard 
power conversion in a compact embedded platform. 

---

# Hardware and Prototype

<img width="1024" height="712" alt="image" src="https://github.com/user-attachments/assets/c7c16b1e-f26d-4c43-960e-f89352be9fdd" />

<img width="541" height="461" alt="1  LORA - GSM Master" src="https://github.com/user-attachments/assets/137fa6b8-eece-48f1-afa0-58c095e2951f" />


---

# Responsibilities 
- Complete PCB design and layout 
- Power architecture definition 
- RF and antenna integration 
- Industrial I/O interface design 
- System bring-up and hardware validation 

---

# Hardware Architecture 
The board is partitioned into functional domains to ensure signal integrity, RF performance, 
and power stability: 
  
i. Power Conversion Stage 
- Wide-range DC input regulated through a high-efficiency switching converter to 
generate rails for digital logic, RF modules, and I/O drivers. 

ii.Control Core 
- MCU subsystem responsible for system control, peripheral coordination, and 
communication management. 

iii. Long-Range RF Communication 
- Integrated RF module connected to an external antenna for long-distance wireless 
connectivity. 

iv. Cellular Communication 
- Cellular modem provides backhaul connectivity to remote servers and cloud 
infrastructure. 

---

# Design Highlights 
- Switching power layout on compact PCB 
- Functional domain separation (power / digital / RF / I/O) 
- Antenna placement and ground reference 
- High-current switching regulator with thermal copper spreading 
- Industrial protection and filtering implementation 
- Decoupling and return-path control for noise containment 
