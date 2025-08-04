# Power System Fault Detection and Classification

This capstone project presents a machine learning-based solution for detecting and classifying different types of faults in a power distribution system using real-time voltage and current phasor data.

## 👩‍💻 Presented By
- **Vinitha Enagandula**
- **Institution:** Jyothishmathi Institute of Technology and Science  
- **Department:** Computer Science and Engineering

---

## 🧠 Problem Statement
Design a model to distinguish between normal operating conditions and faults such as:
- Line-to-Ground (LG)
- Line-to-Line (LL)
- Three-Phase (LLL)

The goal is rapid, reliable fault identification to support grid stability and operational safety.

---

## 💡 Proposed Solution
A supervised machine learning model leveraging electrical measurements (voltage and current phasors) for:
- **Noise Filtering**
- **Feature Extraction** (RMS values, phase differences)
- **Classification** using Random Forest, SVM, XGBoost, or deep learning (CNN/LSTM)

---

## ⚙️ System Development Approach
1. **Data Collection** – Simulated using MATLAB/Simulink
2. **Preprocessing** – Normalize, filter, and segment signals
3. **Model Training** – On labeled datasets
4. **Deployment** – Real-time detection via cloud or edge devices integrated with SCADA systems

---

## 📈 Result
- Successful simulation of normal and fault conditions
- Accurate classification using ML techniques
- Evaluated using precision, recall, F1-score, and inference time

---

## 🧪 Algorithm and Deployment
- Inputs: Time-series voltage & current phasor data (magnitude, phase angle)
- Feature Engineering: RMS, sequence components, rate of change
- Deployment-Ready: Fast inference for substation applications

---

## ✅ Conclusion
The ML-based fault classification system enables:
- Faster detection
- Downtime reduction
- Enhanced grid reliability

---

## 🚀 Future Scope
- Integration into **smart grids** for automated self-healing
- **Edge deployment** in remote substations for low-latency decisions
- Scalability for large, complex power networks

---

## 📚 References
- Based on methodologies inspired by IEEE papers on power system fault detection, ML, PMUs, and smart grid technologies.

---

## 🏅 IBM Certifications
- The project is supported and validated under IBM certification modules.

---

## 🙏 Thank You!
