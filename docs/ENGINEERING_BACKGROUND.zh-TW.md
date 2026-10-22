# 詳細經歷與技術實作 | 陳沛安

> 嵌入式生醫感測、研究儀器與 FPGA 系統

[English](ENGINEERING_BACKGROUND.md) · [繁體中文](ENGINEERING_BACKGROUND.zh-TW.md) · [個人網站／中文](https://peianchen.github.io/peian-chen/) · [個人網站／英文](https://peianchen.github.io/peian-chen/en/) · [Email](mailto:chen861019@gmail.com)

我是陳沛安，目前就讀國立陽明交通大學電機工程博士班，主要投入感測系統與研究設備開發。我的工作從實驗中的量測與控制需求出發，包含裝置韌體、通訊介面、操作軟體與資料處理，讓研究構想具備實際執行與驗證的條件。

在開發過程中，我關注各個部分接在一起後能否可靠運作：資料如何取得與保存、裝置如何控制，以及出現異常時如何追查。目前持續投入低功耗感測、BLE 裝置整合與 FPGA 邏輯設計，並透過實測、模擬與技術文件記錄設計選擇及其限制。

## 工程領域

| 領域 | 實作內容 | 核心技術 |
| --- | --- | --- |
| 穿戴式生醫感測 | 多部位溫度與汗液壓力感測、生理資料同步、裝置歷史紀錄 | Nordic nRF、BLE、MLX90614、Android、Wear OS |
| 裝置到雲端 | 手機資料擷取、離線儲存、裝置識別、身分驗證與研究儀表板 | Kotlin、Jetpack Compose、Room、Firebase、Flask |
| 電化學量測 | 可攜式計時安培量測、單鍵流程、TFT 回饋與 SD 紀錄 | EmStat Pico、C/C++、SPI、MethodSCRIPT |
| 微流體系統 | 幫浦與閥控制、stop-flow 觀測、手機取像與系統整合 | ESP32、PlatformIO、PDMS、微幫浦、Android |
| 太空與生物實驗 | 定時高解析取像與閉迴路微重力模擬運動平台 | ESP32-S3、OV5640、運動控制、PID |
| FPGA 與數位系統 | RTL、FSM、記憶體、處理器、HPS-FPGA 介面與自動檢查 | Verilog、Quartus、Qsys、Questa、DE1-SoC |

## 系統設計重點

- **跨層整合：** 韌體、通訊、應用狀態、資料儲存與分析共同設計。
- **考慮硬體限制：** 納入時序、功耗、記憶體保留、校正、無線行為與實體介面。
- **以證據驗證：** 分別記錄模擬、編譯、實測與實驗驗證，讓讀者了解各階段的成果與限制。
- **研究可用性：** 重視可重現擷取、可解讀資料、操作流程與持續維護。

## 精選公開專案

| 專案 | 說明 | 技術 |
| --- | --- | --- |
| [ThermoPatch](https://github.com/peianchen/ThermoPatch) | 多節點 BLE 體表溫度平台，整合 Android 視覺化、Firebase 同步與 OTA 韌體更新 | Kotlin、Compose、BLE、Firebase、nRF52840 |
| [SpaceCellCam](https://github.com/peianchen/SpaceCellCam) | ESP32-S3／OV5640 定時高解析生物取像，包含 LED 輔助照明與 microSD 紀錄 | C++、Python、ESP32-S3、OV5640 |
| [Space BMC Core RTL](https://github.com/peianchen/Space-BMC-Core-SEMC) | 參數化 Verilog-2001 心跳逾時監測核心，附週期邊界、清除與重新計時檢查 | Verilog、Questa、FPGA |
| [nRF54L15 MLX90614](https://github.com/peianchen/nRF54L15_MLX90614) | XIAO nRF54L15 紅外線溫度感測韌體與低功耗分析 | C、Zephyr、I2C、BLE |
| [Galaxy Watch Sensor Monitor](https://github.com/peianchen/GalaxyWatchSensorMonitor) | Samsung 手錶皮膚溫度擷取與研究型感測應用 | Kotlin、Wear OS、Samsung Health Sensor SDK |
| [資料結構與圖論演算法](https://github.com/peianchen/NYCU-Data-Structures-Graph-Algorithms) | 九份 C 作業：排序、BFS、稀疏矩陣、運算式、Segment Tree、Huffman、MST 與最短路徑，附結果與限制說明 | C、GCC、Python、Graphviz |
| [台北公車 Live](https://github.com/peianchen/taipei-bus-live) | 開發中的公車即時地圖，包含路線／車牌搜尋、標記聚合、路線匹配與官方快照的短時間位置推估 | JavaScript、Node.js、MapLibre GL JS |

**課程實作典藏：** [NYCU-AFPGA](https://github.com/peianchen/NYCU-AFPGA-Labs) 整理八組 Verilog／DE1-SoC 實驗，涵蓋組合邏輯、FSM、RAM、簡易處理器與 HPS/Qsys 整合。公開版本包含整理後的文件、原始碼與實驗圖片。

## 研究經驗

| 平台 | 工程貢獻 |
| --- | --- |
| 微重力模擬系統 | 雙軸 Random Positioning Machine、多軸嵌入式運動控制、感測與影像整合、即時資料擷取 |
| 穿戴式 IoT 裝置 | nRF52840 感測節點、BLE 通訊、手機與雲端資料管理、LVGL 裝置介面 |
| 仿生微流體生醫工程 | 趨溫性／流變性分選、溫度梯度控制、影像式運動分析、自動化資料擷取 |

- **2025：** Texas A&M University 研究發表；北海道大學 RIES-CEFMS Joint Symposium 海報發表。
- **2024：** CES TTA 臺灣科技新創館參展；DMS (NAIST)-CEFMS (NYCU) Joint Symposium 口頭發表；ICSS 海報發表。
- **2023：** 未來科技獎；FITI 創新創業激勵計畫入圍。
- **2021：** 生醫創意構想競賽佳作。
- **2017-2019：** 機器人與 AIoT 競賽經驗，包括 AIoT 智慧機器人、愚公移山與物聯網智慧控制社群成果發表第一名。

[完整網站](https://peianchen.github.io/peian-chen/#research) 保留各項競賽明細與 *Biosensors & Bioelectronics*、*Sensors and Actuators A* 期刊紀錄。

## 教育背景

| 期間 | 學歷 |
| --- | --- |
| 2022-至今 | 國立陽明交通大學電機工程博士班，預計 2027 年 6 月畢業 |
| 2020-2022 | 國立陽明交通大學生醫工程碩士 |
| 2016-2020 | 國立宜蘭大學生物機電工程學士 |

語言：中文、英文、基礎日文。

## 技術能力

以下以專案中的實作能力為主，並列出代表性工具與平台。

### 硬體與數位設計

- **FPGA／RTL 設計：** 數位邏輯實作與 SoC 周邊整合，使用 Verilog、Quartus、Qsys／Platform Designer，具 DE1-SoC 專案經驗
- **數位驗證：** 測試平台開發、波形除錯、狀態控制與資料路徑邏輯的功能驗證，使用 Questa／ModelSim
- **電路與 PCB 設計：** 使用 KiCad 進行電路圖繪製與 PCB 佈線
- **硬體與系統整合：** 軟硬體協同設計、子系統整合與實驗系統開發

### 嵌入式韌體與感測

- **嵌入式平台開發：** 微控制器與單板電腦的裝置韌體及周邊整合，實作平台包含 Nordic nRF、ESP32、Arduino 相容開發板與 Raspberry Pi
- **韌體開發：** C/C++ 韌體、事件驅動控制、狀態機與嵌入式操作介面，使用過 Zephyr／nRF Connect SDK、Arduino、PlatformIO 與 LVGL
- **裝置通訊：** 無線通訊、協定整合與裝置資料交換，具 BLE／GATT、OTA／DFU、I2C、SPI 與 UART 實作經驗
- **低功耗感測：** 量測排程、資料紀錄與保存、電源狀態管理、校正與實測評估

### 軟體開發與資料整合

- **程式開發：** 使用 C/C++、Python、Kotlin 與 JavaScript 開發韌體、應用程式與分析工具，並以 HTML／CSS 建立網頁介面
- **行動應用：** 裝置連動的 Android／Wear OS 應用、介面狀態管理與非同步資料處理，使用 Jetpack Compose、ViewModel、coroutines／Flow 與感測 SDK
- **資料儲存與同步：** 離線儲存、背景處理、身分驗證與裝置到雲端的資料流程，使用 Room／SQLite、WorkManager 與 Firebase
- **網頁與桌面應用：** 互動式儀表板、資料視覺化與分析介面，具 Flask、Node.js、MapLibre GL JS、PyQt5 與 GitHub Pages 專案經驗

### 資料分析與生物影像

- **科學運算：** 數值處理、時間序列分析、特徵萃取與視覺化，使用 Python 科學運算套件，包含 NumPy、pandas、SciPy 與 Matplotlib
- **影像分析：** 生物實驗影像處理流程，包含前處理、分割、配準與運動分析，使用 OpenCV 與 scikit-image
- **研究資料流程：** 資料擷取、標註、視覺化與分析結果比對，具 Python 與 LabVIEW 使用經驗

### 研究系統整合與開發流程

- **研究儀器開發：** 生醫與生物實驗的量測及控制系統開發，應用經驗涵蓋穿戴式感測、電化學、微流體與影像系統
- **運動與回授控制：** 閉迴路控制與多軸系統整合，具 PID 與 Random Positioning Machine 專案經驗
- **開發與除錯：** 版本控制、建置流程、依執行紀錄追查問題與跨層整合測試，使用工具包含 Git、Gradle、GCC、序列埠除錯與 Android Logcat
- **文件與驗證：** 可重現測試流程、技術文件與自動化發布流程，分別記錄模擬、建置與實機量測結果

## 目前方向

- 建立可靠、低功耗的多裝置穿戴式感測流程。
- 整合生理訊號、電化學、微流體與影像資料，支援研究應用。
- 開發附可重現驗證流程的 FPGA 控制與可靠度模組。
- 改進微重力模擬實驗的閉迴路運動平台。

聯絡：**[chen861019@gmail.com](mailto:chen861019@gmail.com)**。完整作品集：[中文版](https://peianchen.github.io/peian-chen/) · [English](https://peianchen.github.io/peian-chen/en/)。
