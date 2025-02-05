# Overview

Open2FA is an application designed for two-factor authentication, featuring an
additional system for transmitting generated codes via QR codes. The primary purpose of the application is to generate one-time codes used for verifying user’s identity during login. Open2FA stands out from other applications by encrypting secrets (keys used to generate the codes) with a password and allowing them to be saved to a file. This enables users to easily transfer their codes to another device by simply sending the file. The application also supports a relay system that facilitates the direct transmission of encrypted one-time codes to another device via QR code scanning.

The entire project consists of three applications:
1. Mobile Application – The main app used for generating and managing
one-time codes.
2. Web Application – A demonstration of the relay system, enabling the reception of one-time codes from a smartphone.
3. Relay Server Application – A system component responsible for transmitting encrypted codes from the phone to the web application. 

# Example films



https://github.com/user-attachments/assets/01bffab6-f11a-4a0e-9301-3c22234915f8



https://github.com/user-attachments/assets/8870e7e3-bd92-44c1-ba68-62d1bd7097dd



https://github.com/user-attachments/assets/a60feed7-4596-4a54-87ef-ff0e47814ce4

