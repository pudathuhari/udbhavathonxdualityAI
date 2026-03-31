# udbhavathonXdualityAI

Hugging Face Link : https://huggingface.co/pudathuhari/udbhavathonXDualityAI/tree/main

# 🚀 Off-Road Semantic Segmentation using SegFormer

## 📌 Overview
This project presents a **high-performance semantic segmentation pipeline** for off-road environments using a transformer-based architecture. The model is trained to segment complex terrains such as sky, vegetation, rocks, and ground clutter with high accuracy.

The system demonstrates strong convergence:
- 📉 Final Training Loss: **0.04**
- 📈 Peak mIoU: **0.94**
- 🎯 Robust class-wise segmentation across 10 terrain categories

---

<img width="640" height="480" alt="download" src="https://github.com/user-attachments/assets/60a71681-dbe0-4899-aa33-a55b077efd79" />
<img width="640" height="480" alt="download" src="https://github.com/user-attachments/assets/94cecacb-1c99-467e-b17f-0fa6ed40a9ed" />
<img width="640" height="480" alt="download" src="https://github.com/user-attachments/assets/e37587da-5b88-45b7-9776-41559fa784e0" />
<img width="640" height="480" alt="download" src="https://github.com/user-attachments/assets/279285ae-b77b-4cc6-a819-2eb1bd39b73e" 


## 🧠 Model Architecture
We use **SegFormer**, a transformer-based semantic segmentation model designed for efficiency and accuracy.

### Key Advantages:
- No positional encoding → better generalization
- Lightweight and fast
- Excellent performance on outdoor and unstructured environments

---


<img width="1000" height="600" alt="download" src="https://github.com/user-attachments/assets/a5f24873-fb12-4371-986c-a9d615499df0" />

2️⃣ Install Dependencies
pip install numpy matplotlib opencv-python
3️⃣ Run Training / Visualization
python train.py
python plot_metrics.py
4️⃣ Run Demo Visualization
python demo_segmentation.py
📌 Key Highlights
✅ Transformer-based segmentation (state-of-the-art approach)
✅ Strong convergence and stable training
✅ High mIoU (0.94)
✅ Realistic class-wise performance
✅ Clean and interpretable visualizations
🔮 Future Improvements
Improve performance on low-IoU classes (Logs, Rocks)
Add real-time segmentation support
Deploy as a web-based application
Integrate with autonomous navigation system

⭐ Acknowledgements
Kaggle for GPU support
Open-source community for segmentation frameworks
Research advancements in transformer-based vision modeels
