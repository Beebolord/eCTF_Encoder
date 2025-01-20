# eCTF_Encoder
Python package Encoder for the ECF 2025!
This encoder accepts three key inputs: Channel Number, Current Timestamp, and TV Frame Data. Notably, Channel 0 is reserved exclusively for Timestamp Encoding in emergency broadcasts, while other channels handle the standard TV frame encoding. The encoder processes these inputs and returns the encoded frame data as a byte sequence. This functionality is critical for satellite uplink decoding in secure communication systems, where global secrets and sensitive information are handled within the encoded frame. The package is part of an innovative solution to manage and transmit broadcast data securely and efficiently, ensuring data integrity and confidentiality during satellite transmissions.
This python package works alongside the design schema presented as-below: 
![image](https://github.com/user-attachments/assets/091f813c-0731-4499-af67-58815eb75e61)
