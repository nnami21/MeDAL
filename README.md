This repository consists of code used to reimplement MeDAL
1) The ARSN and MESSIDOR datset were operated on
2) Global Contrast Normalization was applied to each dataset and each feauture had zero mean
3) The model consisted of a pretrained inception v3 models, dropout, and three linear layers
4) AUC score of MESSIDOR and ARSN baseline were 79.2081% and 52.2731% respectively

After MeDAL technique was applied to ARSN/MESS dataset
1) Best results with MESSIDOR test set: AUC Score: 79.05% and accuracy was 73.5%
2) Best results with ARSN test set: AUC Score: 86.46% and accuracy was 83.33%



Note: My CPU has 700GB of memory, so I didn't use dataloader because I wanted to free the GPU for the model 
