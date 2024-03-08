# FAAB_Financial_Argument_Ananlysis_Bengali
Live demo @ Hugging Face Spaces: https://huggingface.co/spaces/rima357/FinArgBengali
# How to use?
1. In this toolkit, there are two tabs. Tab-1 is used for classifying a Bengali argumentative text into Premise or Claim. Tab-2 is used for detecting the relationship between two Bengali argumentative texts.
2. In Tab-1 you see a textbox where you can enter the text in Bengali or choose the text from examples. Click the "Classify" button to classify the text into Premise or Claim.
3. In tab-2 you see two textboxes for text1 and text2, where you can enter the text in Bengali or choose the text from examples. Click "Detect the relation" button to detect the relation between two bengali texts.
4. In both tabs, you see a "Clear" button to clear the input and output.
5. For code, you can check- https://huggingface.co/spaces/rima357/FinArgBengali/tree/main
6. For demo video, you can check- https://youtu.be/4JwVl4mbj6Q.
#  Output descriptions for both tasks
1. Task-1
   1. Label 0 means Premise.
   2. Label 1 means Claim.
2. Task-2
   1. Label 0 means No relation.
   2. Label 1 means Support.
   3. Label 2 means attack.
# Screenshot of task-1 toolkit: Classify a Bengali argumentative text into Premise or Claim.
![Alt text](https://github.com/rima357/FAAB_Financial_Argument_Ananlysis_Bengali/blob/main/Image_toolkit_task1.png)
# Screenshot of task-2 toolkit: Detect the relation between two Bengali argumentative texts.
![Alt text](https://github.com/rima357/FAAB_Financial_Argument_Ananlysis_Bengali/blob/main/Image_toolkit_task2.png)

```bibtex
@inproceedings{10.1145/3632754.3632763,
author = {Roy, Rima and Ghosh, Sohom and Naskar, Sudip Kumar},
title = {Financial Argument Analysis in Bengali},
year = {2024},
isbn = {9798400716324},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3632754.3632763},
doi = {10.1145/3632754.3632763},
abstract = {Argument mining is an emerging area of research. Argument mining in financial domain specifically for low-resources language like Bengali is in its nascent stage. There exist no datasets for argumentative financial texts mining in Bengali. In this paper, we propose two new datasets in Bengali for financial argument analysis. Subsequently, we released two transformer-based models fine-tuned on these datasets as baselines for financial argumentative unit classification and for detecting the relation between two argumentative financial texts.},
booktitle = {Proceedings of the 15th Annual Meeting of the Forum for Information Retrieval Evaluation},
pages = {88–92},
numpages = {5},
keywords = {Argument Mining, Financial Natural Language Processing, Language Resources in Bengali, Natural Language Processing},
location = {Panjim, India},
series = {FIRE '23}
}
```
