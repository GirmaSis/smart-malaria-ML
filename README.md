## Smart Malaria Classification: A Novel Machine Learning Algorithms for Early Malaria Monitoring and Detecting Using IoT-Based Healthcare Environment

This repository contains the source code and implementation notebooks from the paper:

**Smart Malaria Classification: A Novel Machine Learning Algorithm for Early Malaria Monitoring and Detection using IoT-Based Healthcare Environment**  
Published in *Sensing and Imaging (2024) 25:55*  
[📄 DOI: 10.1007/s11220-024-00503-3](https://doi.org/10.1007/s11220-024-00503-3)

### Notebooks included
- `ANN_Maleria.ipynb` — Artificial Neural Network (ANN) implementation
- `KNN_Maleria.ipynb` — K-Nearest Neighbor (KNN) implementation
- `Malaria_SVM.ipynb` — Support Vector Machine (SVM) implementation
- `Naïve_Bayes_Malaria.ipynb` — Naïve Bayes implementation

Each notebook applies machine learning to classify malaria cases as **Parasitized** or **Normal** based on 15 IoT-sensed symptoms from a Nigerian dataset ([🔗 source](https://doi.org/10.1016/j.dib.2019.104997)).

### Results summary

| Method        | Training Accuracy | Testing Accuracy | AUC Score | F1-Score |
|---------------|-------------------|------------------|-----------|----------|
| **SVM**       | 98%               | 96%              | 95%       | 95%      |
| **ANN**       | 97%               | 93%              | 97%       | 90%      |
| **KNN**       | 97%               | 91%              | 94%       | 84%      |
| **Naïve Bayes** | 61%             | 62%              | 63%       | 46%      |


### Dataset description
- Total records: **1011**
- Features: **15 binary symptoms**
- Classes: **Parasitized** (348 cases), **Normal** (663 cases)

### Environment
- Python
- Google Colab (Jupyter)
- Scikit-learn, Matplotlib, Pandas, Numpy

### Citation
If you use this code, please cite the paper:

```bibtex
@article{ayalew2024smart,
  title={Smart Malaria Classification: A Novel Machine Learning Algorithm for Early Malaria Monitoring and Detection using IoT-Based Healthcare Environment},
  author={Ayalew, Aleka Melese and Admass, Wasyihun Sema and Abuhayi, Biniyam Mulugeta and Negashe, Girma Sisay and Bezabh, Yohannes Agegnehu},
  journal={Sensing and Imaging},
  volume={25},
  pages={55},
  year={2024},
  publisher={Springer}
}
