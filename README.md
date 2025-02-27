## Vending-Machine

![Screenshot 2025-02-27 103525](https://github.com/user-attachments/assets/86c6dfd6-6876-45e2-a793-0e9d63b2ae8c)
This design ensures that vending can only occur if a coin is inserted first, as the SR latch prevents vending without being set. A manual reset may be needed after vending, depending on the circuit’s implementation.

# Coin in
![WhatsApp Image 2025-02-27 at 10 38 40 AM](https://github.com/user-attachments/assets/244d3652-b186-4f98-8bef-2362aa0ca685)
The circuit has two inputs: a COIN button and a VEND button. Pressing COIN represents inserting a coin, while pressing VEND causes the machine to vend an item, indicated by turning on an LED.

# Being Vended
![WhatsApp Image 2025-02-27 at 10 38 48 AM](https://github.com/user-attachments/assets/c2fc82c8-3679-4c09-80c1-c70c286da375)
There are two LED outputs: COIN LED and VEND LED. The COIN LED lights up when a coin is inserted, and the VEND LED lights up when an item is being vended.

# Reset no coin in
![WhatsApp Image 2025-02-27 at 10 38 43 AM](https://github.com/user-attachments/assets/a3f59bab-8b54-4c08-bf15-57e35b20c829)
The machine will not vend an item unless a coin has been inserted first. Only one coin can be inserted at a time, and inserting additional coins does not affect the circuit’s state. Normally, a vending machine resets automatically after dispensing an item, but for simplicity, this design requires a manual reset instead.

# References 
Justice, M. (2020). How Computers Really Work: A Hands-On Guide to the Inner Workings of the Machine. No Starch Press.



