This project was done by my and Aakrishi Tiwari while an internship at Powergrid Corporation Of India
Reason for the development of a system for detecting moisture.

Transformer humidity, stemming from factors like breathing mechanisms, ventilation openings, and environmental conditions, can harm insulation and overall performance. Sources include the transformer's breathing process, ventilation openings, and exposure to high humidity or extreme temperatures. Excess moisture may lead to issues like diminished dielectric strength and accelerated insulation aging. To safeguard transformers, consistent monitoring, maintenance, and the use of effective sealing materials are crucial for reliable, long-term operation.

Solution I came up with

To mitigate the risk of potential transformer damage and associated financial losses, we've introduced an IoT-based system called "Moisture Detection in a Transformer." This system employs silica gel packets with color-changing properties to monitor humidity levels in real-time. To ensure reliable communication in remote areas with limited internet connectivity, the system utilizes LoRa Technology, known for its low-power characteristics and extended range. The LoRa system includes a transmitter with a color sensor detecting silica gel changes and a receiver in the control room. Data is transmitted to an API, which posts information to the database accessible through a website. This approach proves advantageous, especially when transformers are located approximately 2 km from the control room.
