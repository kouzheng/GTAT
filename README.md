## **GTAT: Empowering Graph Neural Networks with Cross Attention**
![image](https://github.com/user-attachments/assets/ba021555-8e02-47d1-b3c3-7a62fc730fa8)

Our framework begins with the topology feature extraction (TFE) for each node. After getting the set of topology representations, we apply Graph Cross Attention (GCA) layers to update node feature representations and topology representations. Lastly, the model utilizes the node feature representations from the final layer to predict node classifications.
The GCA Layewr need three inputs: node representation, edge_index and topology representation.
Reference
Shen, J., Ain, Q.T., Liu, Y. et al. GTAT: empowering graph neural networks with cross attention. Sci Rep 15, 4760 (2025). 
https://doi.org/10.1038/s41598-025-88993-3
