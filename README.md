# NFC Phishing Awareness Lab

Educational cybersecurity awareness project showing how an everyday NFC object can become a social engineering risk.

This repository documents a **controlled lab simulation** using a 3D printed keychain and an NFC tag. The goal is to help people understand how trust, curiosity and convenience can be abused in phishing scenarios.

No real credentials are collected. This project is for **training, awareness and defensive education only**.

![NFC keychain](https://github.com/daniellopezciber/phishing-in-your-pocket/blob/main/llavero%20facebook%201.jpg?raw=true)

## Purpose

The project demonstrates three important ideas:

- Social engineering often targets human trust, not only technical systems.
- NFC technology is convenient, but unknown tags should not be trusted blindly.
- Security awareness becomes stronger when people can see and understand realistic attack paths in a safe environment.

## Scenario

In a real-world phishing scenario, an attacker could hide a URL inside an NFC tag and place that tag inside an object that looks harmless. When a phone scans the tag, the user may be redirected to a page that imitates a trusted service.

This lab reproduces that idea in a controlled and ethical way to explain the risk and teach defensive behavior.

## What This Project Shows

- How NFC tags can store URLs.
- How physical objects can be used in social engineering.
- How brand familiarity can influence user behavior.
- Why URL verification and 2FA matter.
- How to design security awareness material with practical examples.

## Lab Steps

### 1. Keychain Design

![Design in MakerWorld](https://github.com/daniellopezciber/phishing-in-your-pocket/blob/main/dise%C3%B1o%20makerworld.png?raw=true)

A simple keychain was designed as the physical object for the demonstration.

### 2. NFC Space

![Bambu Lab design](https://github.com/daniellopezciber/phishing-in-your-pocket/blob/main/dise%C3%B1o%20bambulab.png?raw=true)

A cavity was added to place a 25 mm NFC tag inside the printed object.

### 3. 3D Printing and Embedding

![Bambu Lab print](https://github.com/daniellopezciber/phishing-in-your-pocket/blob/main/impresion%20bambulab.png?raw=true)

The print was paused at the correct layer, the NFC tag was inserted, and the print continued to encapsulate the tag.

### 4. NFC URL Writing

An educational URL was written to the NFC tag using an NFC writing app. In a malicious scenario, this could be abused to redirect users to unsafe websites.

### 5. Awareness Simulation

![Simulation flow](https://github.com/daniellopezciber/phishing-in-your-pocket/blob/main/nfc.jpg?raw=true)

When the object is scanned, the phone opens the programmed URL. This makes the risk visible and easy to understand for non-technical users.

## Defensive Lessons

- Do not scan unknown NFC tags or QR codes.
- Always verify the domain before entering credentials.
- Use a password manager to detect fake login pages.
- Enable multi-factor authentication.
- Report suspicious objects, links or pages.
- Treat unexpected login prompts with caution.

## Use Cases

This project can be used for:

- Cybersecurity awareness sessions.
- Social engineering training.
- Internal security presentations.
- Demonstrations for non-technical audiences.
- Portfolio evidence for practical security education.

## Ethical Notice

This repository is strictly educational. It must not be used to collect credentials, impersonate services or target real users. The objective is to teach defensive awareness and reduce risk.

## Author

**Daniel Lopez**  
Cybersecurity and AI automation learner focused on practical, ethical and well-documented projects.

- GitHub: [daniellopezciber](https://github.com/daniellopezciber)
- LinkedIn: [Daniel Lopez](https://www.linkedin.com/in/daniel-lopez--garcia/)
