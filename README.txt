# 3D Mesh Normalization, Quantization, and Reconstruction

**Overview**  
This project performs 3D mesh normalization, quantization, dequantization, and reconstruction  
using Python libraries such as **Trimesh**, **NumPy**, and **Matplotlib**.  

It includes:  
- Task 1: Load & Inspect Mesh  
- Task 2: Normalize & Quantize  
- Task 3: Dequantize, Denormalize & Measure Error  

---

**How to Run**  
1. Open Google Colab or Jupyter Notebook.  
2. Upload the **`meshes`** folder with the `.obj` files.  
3. Open **`main.ipynb`** and run all cells.  
4. Outputs (normalized, quantized, reconstructed meshes and plots) will be saved to `/processed_meshes` and `/plots`.  

---

**Dependencies**  
- numpy  
- trimesh  
- matplotlib  
- open3d *(optional)*  

---

**Observations**  
- **Unit Sphere normalization** preserves mesh structure better with lower reconstruction error.  
- **Min–Max normalization** introduces slightly higher per-axis distortion.  
- Reconstruction **MSE/MAE** values confirm this pattern across all sample meshes.  

---

**Author**  
**Kasetty Harsha Vardhan**  
*B.Tech Student*  
