# CSE465_Spring2025_Group-9
### The data is uploaded in 3 different files Train.csv, Test.csv, Val.csv
#### Train.csv
The "Train.csv" file contains two columns named Data, and Label. Which is used to train the llms. 
#### Test.csv
The "Test.csv" file contains two columns named Data, and Label. Which is used to test the llms. 
#### Val.csv
The "Val.csv" file contains two columns named Data, and Label. Which is used to validate the llms. 
#### Dataset:
We collected data from Kaggle. Here we are providing the source of collecting data.
Source:https://www.kaggle.com/datasets/cryptexcode/sentnob-sentiment-analysis-in-noisy-bangla-texts
### Data Visualization
The data were visualized using the dataview.ipynb. Which is not EDA but the preparation section was that. EDA is the next target in future.
### There are 8 LLMs trained on this dataset.
  .BERT
  .Distil-BERT
  .RoBERTa
  .DeBERTa
  .ALBERT
  .XL-NET
  .Google-Electra
  .BanglaBERT
### Best Model save
 We applied eight LLM models for this dataset and get performance for every models. We get best performance by BanglaBERT which is 76%. Firstly, we get 73% accuracy. Then we applied adamW optimizer and get better accuracy. At last, we applied hyper-parameter tuning and get 76% accuracy for that which is the highest accuracy of our work. And we are going to improve it. 

### Save Model Link
Here, we are uploading the best performance model link.
https://drive.google.com/drive/folders/1iQouS4eACJ7GXX6G9k6XpNRsGpJlyazX

### NOTE: The saved model is not uploaded due to the limitation of cloud space in GitHub.

### The testing.ipynb is the notebook file that is used for testing the best models performance after training with a specific training_arguments.

### Next Target 
Our next target will be apply BanglaBERT model and check it's performance. Then we will try to improve it's accuracy and performance by doing fine-tuning and applying optimizers also.

### Team Contribution Table:
|Team Member|Contribution|Model|
|----------|---------------|------|
|S.M. Riaz Rahman Antu|Fine-tuned the model, LoRA-Config, Hyper-Parameter Tuning|BanglaBERT, ALBERT,BERT, Electra|
|Souvik Pramanik|Fine-Tuned the model, Back Translation, Data Augmentation|BanglaBERT, RoBERTa, DeBERTa,Distil-BERT, XL-Net|

**Other Contributions**
|Team Member|Contribution|
|----------|---------------|
|S.M. Riaz Rahman Antu|Written the **testing.ipynb** to predict the saved model|
|Souvik Pramanik|Written the **dataview.ipynb** to visualize the dataset|

### Network Architecture: 
The network architechture of BanglaBERT pretrained model is uploaded in the **Final_update** folder (Final_update/Network Architecture.png). 

### Confusion Matrix:
The confusion matring of the labels are shown in the **Final_update** folder (Final_update/Confusion Matrix.png).

### Classification Report:
The classification report of the final model is uploaded in the **Final_update** folder (Final_update/465_Classification_Report.png)

### Results: 

||precision|recall|f1-score|
|-----|-------|-------|-------|
|Neutral|0.59|0.51|0.55|
|Positive|0.81|0.82|0.81|
|Negative|0.79|0.84|0.82|

**Accuracy : 0.76**
