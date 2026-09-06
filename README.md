# Abhay A Katti
[LinkedIn](https://www.linkedin.com/in/abhayakatti) | [Email](mailto:abhayakatti@gmail.com) | +91 9945667559 | Bengaluru, India

### Aspiring IoT & Data Engineer

Highly motivated Electrical & Electronics Engineering student with a passion for building end-to-end solutions that bridge the gap between physical hardware and cloud-based data.

My experience spans embedded firmware and full-stack IoT systems, from developing Embedded C firmware and working with Zephyr RTOS, Nordic hardware, and I²C drivers to building Python-based data pipelines using Modbus, MQTT, and Firebase. I also have experience with data analysis and visualization. I’m interested in building reliable systems that connect hardware, firmware, and data.

---

## 🛠️ Skills & Technologies

| Category | Technologies |
| :--- | :--- |
| **Languages & Frameworks** | Python (Flask, Pandas, Streamlit), SQL, Embedded C |
| **Systems & Tools** | Linux, Git, systemd, SQLite, MATLAB, Tableau |
| **Firmware & RTOS** | Zephyr RTOS, nRF Connect SDK, DeviceTree, Kconfig |
| **Hardware & Protocols** | Nordic Semiconductor, nRF52, TI C2000, STM32, MSP430, I²C, SPI, BLE|
| **IoT & Backend** | MQTT, Modbus RTU, Flask, Streamlit, Firebase |

---

## 🚀 Projects

### 1. nPM1300 Power Management Driver

* Embedded C · Zephyr RTOS · I²C · DeviceTree

A standalone exploration of low-level PMIC driver development using Zephyr.

* Built an I²C-based driver suite for register-level interaction with the power management IC.
* Implemented functionality for battery charging, BUCK/LDO regulation, and ADC-based voltage/temperature monitoring.
* Integrated the driver with Zephyr using DeviceTree and Kconfig.
* Used Zephyr threads, mutexes, and semaphores to manage shared PMIC state across concurrent tasks.
* Debugged register-level behaviour against the manufacturer’s product specification and validated conversion and control logic.

> Note: This project is a cleaned-up/public version of work explored during my embedded systems internship. Proprietary company code and information are not included.

### 1. Campus Energy Monitoring System (Full-Stack IoT Pipeline)
* **Engineered** an IoT data logger (Python, Modbus RTU) to capture **5 real-time electrical parameters** (e.g., Power, Voltage, Current) from a campus smart meter at a **5-second interval**.
* **Solved** a critical Firebase quota bottleneck (20k writes/day) by architecting an MQTT-based aggregation service; this **reduced daily database writes by over 98%** (from 17k to <300) by batching 60 data points into a 5-minute average.
* **Built and deployed** a Flask (Gunicorn) REST API to serve aggregated data to a live dashboard; managed the **3-tier system** (Logger, Bridge, API) as **3 independent, resilient `systemd` services** for robust 24/7 operation on a Linux server.

### 2. British Airways Customer Satisfaction Dashboard
* **Led** a comprehensive analysis of British Airways customer reviews across categories like entertainment, service, and comfort to identify key areas for improvement.
* **Developed** an interactive Tableau dashboard integrating sentiment analysis and geographical mapping, providing stakeholders with real-time insights into customer feedback trends.

### 3. Jaipur Tourism (Exploratory Data Analysis)
* **Conducted** comprehensive analysis of a dataset encompassing over 70 attractions and 250 hotels to recommend personalized places of interest and accommodations.
* **Employed** Python to perform geographical analysis and route optimization, enhancing tourist experiences by creating efficient travel routes.
* **Contributed** to enhancing user experience by incorporating review-based prioritization and pricing analysis, resulting in improved decision-making for tourists.

### 4. Automobile Bike Co. (Customer Segmentation)
* **Employed** Python and RFM (Recency, Frequency, Monetary) analysis to segment customers into 11 distinct groups, enabling targeted marketing campaigns.
* **Cleaned and analyzed** customer data to identify key purchasing behaviors, trends, and demographic insights (age, gender, wealth).

---

## 💼 Experience

### Sensio Enterprises
> Embedded Intern (Jun 2026 - Jul 2026)

* Developed Embedded C firmware using the Zephyr RTOS and nRF Connect SDK ecosystem for wearable hardware.
* Developed a custom I²C driver stack for a Nordic power management IC, including battery charging, voltage regulation, and ADC-based monitoring.
* Worked with Zephyr DeviceTree, Kconfig, multithreading, and kernel synchronisation primitives for firmware integration.
* Evaluated sensor hardware and explored IoT/wearable product concepts for potential integration into future products.

### Gas Turbine Research Establishment (DRDO)
> Student Trainee (Jun 2025 - Jul 2025)

* Developed and tested embedded C firmware for the **TI TMS320F28069M** microcontroller, configuring GPIO for digital I/O control.
* Implemented a **moving-average filter** to process raw ADC signals, significantly improving data accuracy and stability for sensor inputs.
* Utilized the **ePWM module** to generate precise, variable-duty-cycle waveforms, successfully emulating DAC functionality for control signal output.

### Project Kagadha - EnactusPESU
> Core Member

* Researched, prototyped, and tested an innovative eco-friendly pencil design with seed capsules, contributing to the conversion of over **100 kg of waste paper** into sustainable products.
* Presented findings from market research and product testing to key stakeholders, leading to a **75% increase in funding** for further development.
* Led R&D efforts to optimize the manufacturing process, resulting in a **30% increase in production efficiency** and a 25% reduction in waste.

---

## 🎓 Education

### PES University, Bengaluru
* **Bachelor of Technology (B.Tech) in Electrical & Electronics Engineering** (Expected May 2028)
