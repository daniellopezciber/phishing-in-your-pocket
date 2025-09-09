# 🔑 Phishing in your pocket  
### *The weakest link: how social engineering turns everyday objects into digital threats*  

![nfc-keychain](https://github.com/daniellopezciber/phishing-in-your-pocket/blob/main/llavero%20facebook%201.jpg?raw=true)

---

## 🎯 About this project
Have you ever imagined that a simple keychain could become the entry point to your most valuable passwords?  
This project demonstrates, in a controlled and educational environment, how **NFC technology combined with social engineering** can be used to simulate a phishing attack.  

The goal is to **raise awareness in cybersecurity** by showing how everyday objects can be weaponized if users are not cautious.  

---

## ⚠️ Disclaimer
This repository is **strictly for educational purposes**.  
The content presented here must **not** be used for illegal or malicious activities.  
The project is intended to:  
- Teach about **phishing** and **NFC technology**.  
- Show how **social engineering** exploits human trust.  
- Promote **cybersecurity awareness**.  


---

## 🔍 Theoretical Background  

### 📡 NFC (Near Field Communication)  
NFC is a short-range wireless communication technology widely used in:  
- Contactless payments  
- Public transportation cards  
- Smart access systems  
- Everyday objects like keychains  

Its main advantage is **convenience**: just tap and go.  
However, this same ease can be exploited by attackers to deliver malicious links or trigger unwanted actions without the user noticing.  

---

### 🎭 Phishing  
Phishing is a **social engineering technique** where an attacker tricks a victim into voluntarily revealing sensitive information such as usernames, passwords, or financial details.  

Typical examples include:  
- Fake login pages that imitate trusted services (e.g., Facebook, Gmail).  
- Emails with urgent or threatening language.  
- Malicious links hidden behind convincing messages.  

---

### 🧠 Social Engineering  
Unlike traditional hacking, social engineering focuses on **exploiting human trust instead of breaking technology**.  
It leverages curiosity, fear, or urgency to manipulate people into taking unsafe actions.  

In this project, the combination of **NFC + phishing** illustrates how an everyday object (a simple keychain) could be transformed into a deceptive tool to raise awareness of these threats.  

---


![Phishing flow diagram](https://github.com/daniellopezciber/phishing-in-your-pocket/blob/main/nfc.jpg?raw=true)  
*Flow of a phishing attack using an NFC keychain (educational simulation)*  



---

## 🛠️ Project Steps  

### 1. Designing the keychain  
![step1](https://github.com/daniellopezciber/phishing-in-your-pocket/blob/main/dise%C3%B1o%20makerworld.png?raw=true)  
A 3D keychain was designed using **MakerWorld**, starting with a simple Facebook logo as the base.  
This demonstrates how everyday branding can be leveraged in social engineering attacks.  

---

### 2. Adding NFC space  
![step2](https://github.com/daniellopezciber/phishing-in-your-pocket/blob/main/dise%C3%B1o%20bambulab.png?raw=true)  
A cavity was created in the design to embed a **25mm NFC tag**, ensuring it would be encapsulated during 3D printing.  

---

### 3. Printing & embedding  
![step3](https://github.com/daniellopezciber/phishing-in-your-pocket/blob/main/impresion%20bambulab.png?raw=true)  
During printing, a **pause** was configured at the right layer so the NFC tag could be placed inside before the print continued and sealed it.  

---

### 4. Writing a URL to the NFC tag  
![step4](https://github.com/daniellopezciber/phishing-in-your-pocket/blob/main/pyphisher.png?raw=true)  
Using the **NFC Tools app**, a URL was written onto the NFC tag.  
⚠️ In a real attack this could be a malicious page, but in this project it is only a **safe educational demo**.  

---

### 5. Simulation  
![step5](images/step5-simulation.png)  
When the keychain is scanned, the programmed URL automatically opens on the smartphone, demonstrating how easily a victim could be tricked.  

---

