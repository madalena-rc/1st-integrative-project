# 1st-integrative-project
Website for 1st cycle integrative project in Electrical and Computer Engineering

## About MediVest
MediVest aims to reduce hospital stays by enabling safe, remote monitoring for low-risk patients


### Components
#### Hardware
- Lightweight and comfortable vest for everyday use, which tracks vital data, such as heart rate, oxygem saturation, temperature and fall risk resorting to biometric sensors and an IMU

- An SOS button is available, with an imediate call placed to emergency services

- All data is sent via WI-FI resorting to two ESP32 units

- Vest + dock are powered by long-lasting batteries

#### Software
- Data is updated with new assessements in real time

- Firebase Google CLoud services stores all data receivedfrom the vest

- Data is received on the app and on patient's healthcare provider's central (computer), and treated according to each patient's personal thresholds

- Mobile application allows user to view current vitals customize/edit personal thresholds for each vital, as well as check report history relating to all past data collected by the vest

- App and medical central are both equipped with notification alerts in case of emergency and relating to threshold limits
