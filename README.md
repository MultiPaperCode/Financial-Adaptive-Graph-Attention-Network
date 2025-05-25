

**May 25, 2025**  
# **FinAdaptGAT: Financial Adaptive Graph Attention Network**  

### **1. System Requirements**  
• To run the code, simply install the PyTorch Geometric library: Execute pip install torch_geometric to automatically install all required dependencies (including PyTorch). After installation, verify success by running import torch_geometric.

Note: See complete documentation at PyG Official Site.

# Optional dependencies:
pip install pyg_lib torch_scatter torch_sparse torch_cluster torch_spline_conv -f https://data.pyg.org/whl/torch-2.6.0+cpu.html
• Provided as **Jupyter Notebook** for out-of-the-box execution (no additional `requirements.txt` needed)  

### **2. Learning Resources**  
For foundational GNN knowledge, we recommend:  
📚 **[Graph Neural Networks Tutorial Series]**  
(https://www.youtube.com/watch?v=JtDgmmQ60x8&list=PLGMXrbDNfqTzqxB1IGgimuhtfAhGd8lHF)  

**Key Concept Illustrations:**  
![GAT Architecture](https://github.com/user-attachments/assets/5950746a-4c66-43ce-bc24-4e11481379d3)  
![Message Passing Mechanism](https://github.com/user-attachments/assets/6e11f040-5c6a-4e91-9e83-0d0954df9cf6)  
![Node Aggregation Process](https://github.com/user-attachments/assets/e8620569-55f5-455f-a8f9-deb6df43efdc)  


### **3. Framework Overview**  
![FinAdaptGAT Architecture](https://github.com/user-attachments/assets/93a8c9da-8243-4471-b0c3-8d00997fb182)  

### **4. Core Innovations**  
• **Market Behavior Modeling**: Constructs **inter-stock correlation graphs** by simulating investor decision-making processes  
• **Financial-Specific Activation Function**: Novel nonlinear transformation unit optimized for market data characteristics. For more details, please refer to the blog: https://www.cnblogs.com/shiyublog/p/11121839.html.https://www.cnblogs.com/shiyublog/p/11121839.html.
📄 Full implementation details in our paper:  
*"Financial Adaptive Graph Attention Network for Inter-stock Forecasting"*  

**Notes:**  
1. All images are hosted in GitHub user attachments  
2. Notebook-based design enables modular debugging and interactive visualization  

---

### **Key Features**  
✔ **Plug-and-play** implementation  
✔ **Investor behavior-informed** graph construction  
✔ **Domain-optimized** neural components  

