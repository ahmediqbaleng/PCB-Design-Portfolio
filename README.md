# PCB-Design-Portfolio
This is my PCB design portfolio, where I show and discuss my recent circuit design projects. I design my circuits in KiCAD, though I have previous experience with Altium. 

Design 1: ESP32 Bluetooth DAC - Compatible with BMW E9X Media Controls
![Alt Text]([ESP32_DAC_v4 3d vide.png](https://github.com/ahmediqbaleng/PCB-Design-Portfolio/blob/ccb9b314185d165c1d6f9fcecb232e985503f5ee/ESP32_DAC_v4%203d%20vide.png))
  Objective: Implement a seamless Bluetooth audio interface with my BMW E90 3 Series (non-iDrive), with working media controls. In addition, leave provisioning for more devices in the future, like gauges and media displays. 
  
  Key Specifications: 
  * 2 Layer, FR4
  * 85x46 mm
  * UART, I2C, I2S, TWAI
  * 2-Step voltage step down (12V->5V->3.3V)
  * Separate digital and audio LDOs
  * Automotive grade electrical protection (fuse, LP filter, reverse polarity, Transient voltage suppresion)
  * Components:
      * ESP32-WROOM32-UE
      * TI PCM5102A DAC
      * SN65HVD230 CAN transciever - with voltage surge protection
   
  Schematic Design:
  * Schematic:
  
    * Power Distribution:
    * DAC Audio:
    * CAN Transiever:
    * ESP32:
      
  * Flow Chart:
  
  PCB Layout & Design Rules:
  
  Manufacturing & Validation (DFM):
  
  Final Assembly:

