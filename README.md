#  Guardian Alert  
### A Wearable SOS Safety Device for Emergencies  

Guardian Alert is a smart IoT-based wearable safety device designed to provide instant assistance during emergency situations. Powered by the ESP32-C3 microcontroller, the device combines real-time GPS tracking, GSM-based SMS alerts, and an audible buzzer system to ensure fast and reliable response — without depending on smartphones or internet connectivity.



# Problem Statement

In emergency situations, relying on smartphones may not always be practical. Users may:

- Be unable to unlock or access their phone
- Have no internet connectivity
- Be in high-stress situations requiring instant action

Guardian Alert solves this by offering a **one-press SOS system** that immediately activates emergency protocols.



# Key Features

-  **One-Press SOS Activation**
-  **Real-Time GPS Location Tracking**
-  **GSM-Based Emergency SMS Alerts**
-  **Loud Buzzer for Nearby Attention**
-  **Second Press Deactivation Feature**
-  **Compact 3D-Printed Wearable Design**
-  **Low Power Consumption**
-  **Works Without Internet (GSM-Based)**



# System Architecture

The device is built using:

- **ESP32-C3 Microcontroller** (Core Controller)
- **GPS Module** (Location Tracking)
- **GSM Module** (SMS Transmission)
- **SOS Push Button**
- **High-Intensity Buzzer**
- **3D-Printed Wearable Casing**



# Working Mechanism

# First Press (SOS Trigger)

1. Buzzer activates immediately.
2. GPS module retrieves real-time coordinates.
3. ESP32-C3 processes location data.
4. GSM module sends emergency SMS with location to trusted contact.
5. Buzzer remains active until deactivated.

# Second Press (Deactivate)

- Buzzer turns OFF.
- No further alerts are sent.
- System returns to standby mode.



# Why GSM Instead of Internet?

- Works without Wi-Fi or mobile data
- More reliable in low-network conditions
- Direct SMS delivery (no middle application)
- Faster emergency response



# Advantages

- Instant emergency response
- Accurate real-time location sharing
- Internet-independent communication
- Lightweight & wearable design
- Energy-efficient system
- User-friendly interface (single button control)



# Performance Highlights

- High SMS delivery accuracy using GSM
- Fast GPS location acquisition
- Minimal latency during SOS activation
- Long battery life due to low-power components



# Future Enhancements

-  Mobile App for Contact Management
-  Automated Voice Alert System
-  Fall Detection for Elderly Care
-  Vehicle Accident Detection Integration
-  Live Location Tracking Dashboard
-  Direct Emergency Service Integration



# Conclusion

Guardian Alert is a compact, reliable, and internet-independent wearable safety solution designed to provide immediate assistance during emergencies. By integrating GPS tracking, GSM communication, and an audible alarm system, it enhances personal security and ensures timely intervention when it matters most.
