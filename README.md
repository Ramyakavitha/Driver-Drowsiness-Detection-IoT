# Driver Drowsiness Detection using IoT

## **Project Overview**
Driver drowsiness is a major cause of road accidents. This project uses an **Eye Blink Sensor** and **NodeMCU (ESP8266)** to detect driver fatigue. When drowsiness is detected (eyes closed beyond a safe limit), a **buzzer/motor alert** is triggered.  
The Blynk-enabled version also **sends real-time alerts to a mobile app**, making it a smart IoT solution for driver safety.

---

## **Features**
- Real-time **drowsiness detection** using Eye Blink Sensor  
- **Buzzer & motor alerts** for immediate driver wake-up  
- **Blynk integration** for live monitoring and notifications  
- Low-cost and portable design for vehicles  

---

## **Technologies Used**
- **Hardware:** NodeMCU (ESP8266), Eye Blink Sensor, Relay, Buzzer, DC Motor, Battery
- **Programming:** Arduino (Embedded C), Blynk API
- **Tools:** Arduino IDE, Blynk Cloud, Serial Monitor

---

## **Circuit Diagram**
![Circuit Diagram](docs/circuit_diagram.png)

**Connections:**  
- Eye Blink Sensor → D8  
- Buzzer → D7  
- Motor (via relay) → D2  
- NodeMCU powered via USB or 9V Battery  

---

## **How It Works**
1. Eye Blink Sensor detects the driver's eye state.  
2. If eyes remain **closed beyond the threshold**, the **buzzer/motor is triggered**.  
3. **Blynk App** displays live alerts and logs drowsiness events.  

---

## **Setup & Installation**
1. Install **Arduino IDE** & **ESP8266 Board Manager**  
2. Install **Blynk Library** (`BlynkSimpleEsp8266.h`)  
3. Replace `BLYNK_AUTH_TOKEN`, `SSID`, `PASSWORD` in code with your credentials  
4. Upload code to NodeMCU  
5. Open Blynk App → Create project → Add Event Logger & Display  

---

## **Future Enhancements**
- Camera-based detection using **OpenCV**  
- **SMS/WhatsApp alerts** for family members  
- Mobile dashboard with trip & drowsiness analytics  

---

## **Author**
**Ramya K**  
[LinkedIn](https://linkedin.com/in/ramyakavitha77) | [GitHub](https://github.com/Ramyakavitha)
