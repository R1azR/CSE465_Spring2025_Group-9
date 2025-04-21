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
 We applied eight LLM models for this dataset and get performance for every models. We get best performance by BanglaBERT which is 75%. Firstly, we get 73% accuracy. Then we applied adamW optimizer and get better accuracy. At last, we applied hyper-parameter tuning and get 75% accuracy for that which is the highest accuracy of our work. And we are going to improve it. 

### Save Model Link
https://drive.google.com/drive/folders/1WsDCZ8G6ePfvoOMLwocR-NCXmZr9JqTx

### NOTE: The saved model is not uploaded due to the limitation of cloud space in GitHub.

### The testing.ipynb is the notebook file that is used for testing the best models performance after training with a specific training_arguments.

### Next Target 
Our next target will be apply BanglaBERT model and check it's performance. Then we will try to improve it's accuracy and performance by doing fine-tuning and applying optimizers also.
