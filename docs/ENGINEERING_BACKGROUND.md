# Engineering Background | Pei An Chen

> Embedded biomedical sensing, research instrumentation, and FPGA systems

[English](ENGINEERING_BACKGROUND.md) · [繁體中文](ENGINEERING_BACKGROUND.zh-TW.md) · [Portfolio / 中文](https://peianchen.github.io/peian-chen/) · [Portfolio / English](https://peianchen.github.io/peian-chen/en/) · [Email](mailto:chen861019@gmail.com)

I am Pei An Chen, a **Ph.D. student in Electrical Engineering at National Yang Ming Chiao Tung University (NYCU)**, Taiwan. I develop sensing systems and research equipment around the measurement and control needs of experiments. My work includes device firmware, communication interfaces, application software, and data processing to turn research ideas into systems that can be operated and evaluated.

![Verilog](https://img.shields.io/badge/Verilog-1E4A7A?style=flat-square)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Zephyr](https://img.shields.io/badge/Zephyr_RTOS-684D8A?style=flat-square&logo=zephyrproject&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![FPGA](https://img.shields.io/badge/FPGA-RTL_Design-C63C15?style=flat-square)

I focus on how the parts work together: acquiring and preserving data, controlling devices, and tracing faults when something goes wrong. My current work centers on low-power sensing, BLE device integration, and FPGA logic design. I use measurements, simulation, and technical documentation to explain design decisions and their limits.

## Engineering Portfolio

| Domain | What I build | Core technologies |
| --- | --- | --- |
| Wearable biosensing | Multi-location temperature and sweat-pressure sensing, synchronized physiological data, and device history | Nordic nRF, BLE, MLX90614, Android, Wear OS |
| Embedded-to-cloud platforms | Mobile acquisition, offline persistence, device identity, authenticated synchronization, and research dashboards | Kotlin, Jetpack Compose, Room, Firebase, Flask |
| Electrochemical instrumentation | Portable chronoamperometry systems with single-button workflows, TFT feedback, and SD logging | EmStat Pico, C/C++, SPI, MethodSCRIPT |
| Microfluidic systems | Pump and valve sequencing, stop-flow observation, smartphone imaging, and payload integration | ESP32, PlatformIO, PDMS, micropumps, Android |
| Space and biological experiments | Periodic high-resolution imaging and feedback-controlled reduced-gravity motion platforms | ESP32-S3, OV5640, closed-loop control, PID |
| FPGA and digital systems | Verilog RTL, state machines, memories, processors, HPS-FPGA integration, and self-checking verification | Verilog, Quartus, Qsys, Questa, DE1-SoC |

## System Design Focus

- **Cross-layer integration**: firmware, communication, application state, persistence, and analysis are designed as one system.
- **Hardware-aware software**: timing, power, memory retention, calibration, radio behavior, and physical interfaces are treated as design constraints.
- **Evidence-based validation**: simulation, successful builds, bench measurements, and experimentally verified behavior are documented separately.
- **Research usability**: projects emphasize reproducible acquisition, interpretable data, clear procedures, and maintainable iteration.

## Featured Projects

| Project | Description | Technologies |
| --- | --- | --- |
| [ThermoPatch](https://github.com/peianchen/ThermoPatch) | Multi-sensor BLE body-temperature platform with Android visualization, Firebase synchronization, and OTA firmware updates | Kotlin, Jetpack Compose, BLE, Firebase, nRF52840 |
| [SpaceCellCam](https://github.com/peianchen/SpaceCellCam) | ESP32-S3 and OV5640 platform for periodic, LED-assisted high-resolution biological imaging | C++, Python, ESP32-S3, OV5640, microSD |
| [Space BMC Core RTL](https://github.com/peianchen/Space-BMC-Core-SEMC) | Parameterized Verilog-2001 heartbeat timeout monitor with cycle-accurate boundary, clearing, and restart checks | Verilog, Questa, FPGA |
| [nRF54L15 MLX90614](https://github.com/peianchen/nRF54L15_MLX90614) | Zephyr/NCS infrared-temperature firmware and low-power analysis for the XIAO nRF54L15 | C, Zephyr, I2C, BLE |
| [Galaxy Watch Sensor Monitor](https://github.com/peianchen/GalaxyWatchSensorMonitor) | Wear OS application for Samsung skin-temperature acquisition and sensor research | Kotlin, Wear OS, Samsung Health Sensor SDK |
| [Data Structures & Graph Algorithms](https://github.com/peianchen/NYCU-Data-Structures-Graph-Algorithms) | Nine C assignments covering sorting, BFS, sparse matrices, expression evaluation, segment trees, Huffman coding, MST, and shortest paths, with documented results and limitations | C, GCC, Python, Graphviz |
| [Taipei Bus Live](https://github.com/peianchen/taipei-bus-live) | Beta real-time bus map with route and vehicle search, marker clustering, route matching, and short-term position estimation from official snapshots | JavaScript, Node.js, MapLibre GL JS |

**Coursework archive:** [NYCU-AFPGA](https://github.com/peianchen/NYCU-AFPGA-Labs) contains eight documented Verilog and DE1-SoC labs, from combinational logic and FSMs to RAM, processors, and HPS/Qsys integration. The public edition includes curated documentation, source and experiment images.

## Research Experience

| Platform | Engineering contributions |
| --- | --- |
| Microgravity simulation | Dual-axis Random Positioning Machine, embedded multi-axis motion control, sensor and imaging integration, and real-time acquisition |
| Wearable IoT devices | nRF52840 sensing nodes, BLE communication, mobile and cloud data management, and LVGL device interfaces |
| Biomimetic microfluidic bioengineering | Thermotaxis/rheotaxis-based sorting, temperature-gradient control, image-based motion analysis, and automated acquisition |

- **2025:** Research presentation at Texas A&M University; poster at the RIES-CEFMS Joint Symposium, Hokkaido University.
- **2024:** CES TTA Taiwan Tech Pavilion exhibition; oral presentation at the DMS (NAIST)-CEFMS (NYCU) Joint Symposium; ICSS poster presentation.
- **2023:** Future Tech Award; selected for the FITI Innovation & Entrepreneurship Program.
- **2021:** Honorable mention in a biomedical innovation concept competition.
- **2017-2019:** Robotics and AIoT competition experience, including first-place results in AIoT robotics, Moving Mountains, and an IoT intelligent-control community showcase.

The [full portfolio](https://peianchen.github.io/peian-chen/en/#research) retains the detailed competition archive and journal records for *Biosensors & Bioelectronics* and *Sensors and Actuators A*.

## Education

| Period | Education |
| --- | --- |
| 2022-present | Ph.D. student, Electrical Engineering, NYCU; expected June 2027 |
| 2020-2022 | Master's degree, Biomedical Engineering, National Yang Ming Chiao Tung University |
| 2016-2020 | Bachelor's degree, Biomechatronic Engineering, National Ilan University |

Languages: Chinese, English, and basic Japanese.

## Technical Skills

Selected capabilities and representative tools from my project work.

### Hardware & Digital Design

- **FPGA / RTL Design:** digital logic implementation and SoC peripheral integration using Verilog, Quartus, and Qsys / Platform Designer, with DE1-SoC project experience
- **Digital Verification:** testbench development, waveform-based debugging, and functional verification of stateful and datapath logic using Questa/ModelSim
- **Circuit & PCB Design:** schematic capture and PCB layout using KiCad
- **Hardware & System Integration:** hardware-software co-design, subsystem integration, and experimental system development

### Embedded Firmware & Sensing

- **Embedded Platform Development:** device firmware and peripheral integration across microcontroller and single-board-computer platforms, including Nordic nRF, ESP32, Arduino-compatible boards, and Raspberry Pi
- **Firmware Development:** C/C++ firmware, event-driven control, state machines, and embedded user interfaces; experience with Zephyr / nRF Connect SDK, Arduino, PlatformIO, and LVGL
- **Device Connectivity:** wireless communication, protocol integration, and device data exchange, with BLE/GATT, OTA/DFU, I2C, SPI, and UART project experience
- **Low-Power Sensing:** acquisition scheduling, persistent data logging, power-state management, calibration, and measurement-based evaluation

### Software & Data Integration

- **Programming:** firmware, application, and analysis-tool development using C/C++, Python, Kotlin, and JavaScript; web interface development with HTML/CSS
- **Mobile Applications:** device-connected Android and Wear OS applications, UI state management, and asynchronous data processing using Jetpack Compose, ViewModel, coroutines / Flow, and sensor SDKs
- **Data Persistence & Synchronization:** offline storage, background processing, authentication, and device-to-cloud data flows using Room / SQLite, WorkManager, and Firebase
- **Web & Desktop Applications:** interactive dashboards, data visualization, and analysis interfaces, with Flask, Node.js, MapLibre GL JS, PyQt5, and GitHub Pages project experience

### Data Analysis & Biological Imaging

- **Scientific Computing:** numerical processing, time-series analysis, feature extraction, and visualization using the Python scientific stack, including NumPy, pandas, SciPy, and Matplotlib
- **Image Analysis:** image-processing workflows for biological experiments, including preprocessing, segmentation, registration, and motion analysis using OpenCV and scikit-image
- **Research Data Workflows:** acquisition, annotation, visualization, and analysis-result comparison, with Python and LabVIEW experience

### Research Systems & Engineering Workflow

- **Research Instrumentation:** measurement and control system development for biomedical and biological experiments, with wearable sensing, electrochemistry, microfluidics, and imaging applications
- **Motion & Feedback Control:** closed-loop control and multi-axis system integration, with PID and Random Positioning Machine project experience
- **Development & Debugging:** version control, build workflows, log-based diagnosis, and cross-layer integration testing; tools include Git, Gradle, GCC, serial diagnostics, and Android Logcat
- **Documentation & Validation:** reproducible test procedures, technical documentation, and automated publishing workflows, with simulation, build results, and bench measurements documented separately

## Current Direction

- Building reliable low-power, multi-device wearable sensing workflows
- Integrating biosignal, electrochemical, microfluidic, and imaging data into research-ready systems
- Developing FPGA control and reliability modules with reproducible verification
- Improving closed-loop motion platforms for reduced-gravity experiments

Contact: **[chen861019@gmail.com](mailto:chen861019@gmail.com)**. See the [Chinese website](https://peianchen.github.io/peian-chen/) or [English website](https://peianchen.github.io/peian-chen/en/) for the complete portfolio.

![Top languages](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=peianchen&theme=github)
