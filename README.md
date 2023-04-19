## Parameter Optimization of SVM
* SVM stands for Support Vector Machine.
* It is an supervised learning algorithm which is used for Classification as well as Regression problems. 
* Parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning.

### Dataset
**Name:** EEG Eye State Data Set

**Link:** https://archive.ics.uci.edu/ml/datasets/EEG+Eye+State

**Instances:** 14980

**Attributes:** 15

### Methodology
1) Import the necessary libraries.
2) Upload the multi-class dataset from UCI library. 
3) Divide the data into 70-30 for training and testing with 10 different samples.
4) Optimize SVM for each sample with 1000 iterations.
5) Report the best parameter with best accuracy and plot convergence graph.

### Result:
![image](https://user-images.githubusercontent.com/74912353/233191838-77d0f613-2464-4514-a366-1e66d5a92f9b.png)

### Convergence Graph:
![image](https://user-images.githubusercontent.com/74912353/233192106-48dc15ae-bb68-4afb-9272-0bb3b77b020b.png)

### Conclusion:
Best Sample: 5

Best Accuracy: 0.88

Best Kernel: rbf

Best Nu: 0.18

Best Epsilon: 0.69

---

