# 陳沛安 | Pei An Chen

**嵌入式生醫感測 · 研究儀器 · FPGA 數位系統**

[個人網站](https://peianchen.github.io/peian-chen/) · [English](README.md) · [Email](mailto:chen861019@gmail.com)

目前就讀國立陽明交通大學電機工程博士班，預計 2027 年 6 月畢業。我從實驗中的量測與控制需求出發，開發感測裝置、韌體與操作軟體。

我的工作串接物理訊號與可使用的資料，涵蓋取樣排程、裝置通訊、應用程式狀態、儲存與分析。各專案記錄設計選擇，並區分軟體檢查、模擬與實體量測結果。

## 代表作品

| 專案 | 核心問題 | 深入閱讀 |
| --- | --- | --- |
| **ThermoPatch** | 多個 BLE 感測貼片，如何共用清楚的監看與韌體維護流程？ | [專案介紹](https://peianchen.github.io/peian-chen/projects/thermopatch/) · [Android 程式](https://github.com/peianchen/ThermoPatch) |
| **SpaceCellCam** | 照明、對焦、相機記憶體與 SD 寫入，如何安排為可追蹤的取像週期？ | [專案介紹](https://peianchen.github.io/peian-chen/projects/spacecellcam/) · [韌體](https://github.com/peianchen/SpaceCellCam) |
| **Space BMC Core** | 心跳中斷後，哪一個時脈邊緣應觸發逾時，又由什麼條件清除？ | [專案介紹](https://peianchen.github.io/peian-chen/projects/space-bmc/) · [RTL 與 testbench](https://github.com/peianchen/Space-BMC-Core-SEMC) |

## 研究與工程方向

- **感測與連網裝置：** Nordic nRF、Zephyr、BLE/GATT、Android/Compose、Wear OS 與裝置到雲端的資料流程。
- **實驗儀器：** 電化學擷取、幫浦與閥序列控制、生物影像及回授運動控制。
- **數位系統：** Verilog、狀態機、記憶體介面、HPS/FPGA 整合與自動檢查驗證。

[研究平台與發表](https://peianchen.github.io/peian-chen/#research) · [詳細經歷與技術實作](docs/ENGINEERING_BACKGROUND.zh-TW.md)

## 其他公開專案

| 專案 | 內容 |
| --- | --- |
| [nRF54L15 × MLX90614](https://github.com/peianchen/nRF54L15_MLX90614) | Zephyr/NCS 紅外線溫度擷取與 BLE 韌體 |
| [Galaxy Watch Sensor Monitor](https://github.com/peianchen/GalaxyWatchSensorMonitor) | Wear OS 單次皮膚溫度量測 |
| [台北公車 Live](https://github.com/peianchen/taipei-bus-live) | 使用官方快照資料的互動公車地圖，仍為 beta |

## 研究所課程實作

| 主題 | 內容 |
| --- | --- |
| [NYCU-AFPGA](https://github.com/peianchen/NYCU-AFPGA-Labs) | 八組 Verilog／DE1-SoC 實驗，附原始碼、方法、歷史結果圖與分析 |
| [醫學影像深度學習](https://github.com/peianchen/NYCU-Deep-Learning-Medical-Image-Analysis) | 五份分類、分割與偵測作業，提供程式與彙整結果 |
| [資料結構與圖論演算法](https://github.com/peianchen/NYCU-Data-Structures-Graph-Algorithms) | 九份 C 作業，包含實作、複雜度分析與結果 |

## 教育背景

- **2022–至今：** 陽明交通大學電機工程博士班，預計 2027 年 6 月畢業。
- **2020–2022：** 陽明交通大學生醫工程碩士。

程式未公開的研究項目，可在[網站專案區](https://peianchen.github.io/peian-chen/#projects)閱讀用途與系統說明；公開程式則提供可直接閱讀的 repository 連結。
