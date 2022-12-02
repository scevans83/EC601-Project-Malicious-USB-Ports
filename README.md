# EC601_WifiDuck_Project

Introduction

Connecting to charging stations in public spaces such as airports or coffee shops is a seemingly harmless activity. However, when a user connects to these ports, they are oblivious to what is connected behind the scenes. Any of these charging stations could be compromised by attackers looking to steal information from unsuspecting users. During this project we will investigate what vulnerabilities a compromised port exposes a device to, analyze how this is possible by replicating attacks using a WiFi Duck and determine how users can protect themselves and their information.

Brief Wifi Duck Information
The WiFi Duck is a popular hacking device created by Stefan Kremser. It acts as a keyboard when it is inserted into a target computer and gives another device the ability to connect to the targeted computer and upload potentially disastrous payloads. We will create our own malicious socket using the Wifi Duck to replicate and analyze attacks via bad USB ports.

The device consists of a micro-Arduino - which acts as the USB keyboard for input, a microcontroller – which acts as the WiFi access point and a WiFi module which allows an external device to connect to the targeted computer.
![image](https://user-images.githubusercontent.com/93225913/205218187-9fe0e6b6-e891-4cac-bc73-1258d9c602e6.png)
