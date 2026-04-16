# 👋 Hi! I'm Felix Lee

## 中英文自我介紹 / About Me

### 中文

我是 Felix Lee，畢業於 **中興大學（NCHU）電機所碩士班，系統晶片組**。  
目前在職 **AI 工程師 (ML Engineer)**，專注於端到端 Edge AI 系統開發：從模型訓練、INT8 量化編譯，到多平台推論部署與現場調適。

目前主導專案：
- **人臉辨識門禁系統** — 在 Xilinx KV260（FPGA）與 ARK-3533（Intel x86）上部署 RetinaFace + 人臉辨識模型，涵蓋偵測、對齊、嵌入比對完整 Pipeline
- **模型量化與加速** — 使用 Vitis AI (xmodel) 進行 INT8 PTQ/QAT，解決 GDConv 量化崩潰等底層問題；同步以 OpenVINO、ONNX Runtime 做 x86 推論加速
- **多平台 Pipeline** — 同一套系統跨 KV260 / ARK-3533 / PC GPU 部署，各平台效能分析（RAPL / INA260 / nvidia-smi 功耗量測）

專長：
- Edge AI 部署：Vitis AI、OpenVINO、ONNX Runtime
- 模型量化與壓縮（INT8 PTQ/QAT，量化誤差根因分析）
- 即時電腦視覺 Pipeline（人臉偵測、辨識、嵌入比對）
- Python 自動化與工具開發

興趣：
- 喜歡將複雜數據轉化為直觀、有用的資訊，並善於整合 API 與自動化流程來解決實際問題。

---

### English

Hi! I'm Felix Lee.  
I graduated from **National Chung Hsing University (NCHU), Master's Program in Electrical Engineering, System-on-Chip (SoC) Group**.  
Currently working as a **Machine Learning Engineer**, focused on end-to-end Edge AI system development — from model training and INT8 quantization to multi-platform deployment and real-world tuning.

Current project:
- **Face Recognition Access Control System** — deployed RetinaFace + face recognition models on Xilinx KV260 (FPGA) and ARK-3533 (Intel x86), covering full pipeline: detection, alignment, and embedding matching
- **Model Quantization & Acceleration** — INT8 PTQ/QAT via Vitis AI (xmodel), root-caused and resolved GDConv quantization collapse; parallel x86 acceleration with OpenVINO and ONNX Runtime
- **Multi-platform Pipeline** — same system deployed across KV260 / ARK-3533 / PC GPU, with per-platform power profiling (RAPL / INA260 / nvidia-smi)

Expertise:
- Edge AI deployment: Vitis AI, OpenVINO, ONNX Runtime
- Model quantization & compression (INT8 PTQ/QAT, quantization error analysis)
- Real-time computer vision pipeline (face detection, recognition, embedding)
- Python automation and tooling

Hobbies:
- Enjoy turning complex data into actionable insights and automating workflows by integrating APIs and intelligent scripts.
