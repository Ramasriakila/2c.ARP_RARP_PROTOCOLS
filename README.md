# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.

## PROGRAM - ARP
![Screenshot 2025-04-29 232626](https://github.com/user-attachments/assets/ed49aa39-9076-4d26-9523-e9c8dbdb3739)

## OUPUT - ARP
![Screenshot 2025-04-29 232923](https://github.com/user-attachments/assets/0d9bb3b0-c61e-4276-8e90-865c02cb39ba)

## PROGRAM - RARP
![Screenshot 2025-04-29 231316](https://github.com/user-attachments/assets/abbb7351-065d-4089-96e1-08538f004330)

## OUPUT -RARP
![Screenshot 2025-04-29 231838](https://github.com/user-attachments/assets/2276607b-f766-4751-a1c5-f2ce41a43c7e)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
