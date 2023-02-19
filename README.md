# Sampling
Implements Sampling on a given datset
# Sampling
Sampling is the process of selecting a subset of data from a larger dataset.
##
In this, we are applying five different sampling techniques on Credit card Fraud detection dataset.We will further analyze their accuracies and discuss the results.<br>
## Methodolgy
### 1. Converting Imbalanced dataset to balanced dataset: <br>
   In the given dataset, the class '1' has less number of samples. We solved this issue by oversampling class '1' instances
   and making them equal to class '0' instances.
   
### 2. Generating samples using five different sampling techniques: <br>
   1. Simple Random Sampling : A simple random sample is a subset of individuals chosen from a larger set in which a subset of individuals are chosen randomly, all with the same probability. We found the sample size using Sample size detection formula :

   2. Systematic Sampling : Systematic sampling is a probability sampling method where researchers select members of the population at a regular interval. We defined the step size by passing the arguments. 
      
   3. Stratified Sampling : Stratified sampling is a method of sampling from a population which can be partitioned into subpopulations. Here it is based on the class attribute. Then we select equal number of instances of both the subpopulations.
      
   4. Cluster Sampling : A probability sampling method in which you divide a population into clusters   and then randomly select some of these clusters as your sample. 
  
|  | Logistic Regression | SVM | Light Gradient Boosting Machine | Decision Tree Classifier | K Neighbors Classifier |
|----------|----------|----------|----------|----------|----------|
| Random Sampling | 93.83% | 67.00% | 99.43% | 99.25% | 94.20% |
| Systematic Sampling | 93.45% | 60.00% | 98.88% | 99.06% | 97.20% |
| Cluster Sampling | 94.01% | 67.6% | 99.98% | 98.88% | 96.07% |
| Stratified Sampling | 92.16% | 70.55% | 99.63% | 97.76% | 96.06% |

## Conclusion
 Light Gradient Boosting Machine  is giving the best result in each sample.
