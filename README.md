# AWS-Machine-Learning-Specialty

![Alt Text](https://miro.medium.com/max/513/1*YJIqo0jSZsLF0I9qaRs4RA.png)


AWS Machine Learning-Specialty-  notes 

-----------------

- AWS course page: https://aws.amazon.com/certification/certified-machine-learning-specialty/
- AWS exam guide: https://d1.awsstatic.com/training-and-certification/docs-ml/AWS%20Certified%20Machine%20Learning%20-%20Specialty_Exam%20Guide%20(1).pdf
- AWS sample questions: https://d1.awsstatic.com/training-and-certification/docs-ml/AWS%20Certified%20Machine%20Learning%20-%20Specialty_Sample%20Questions.pdf

-----------------------------------------

#### Domain 1: Data Engineering (20%)
Create data repositories for machine learning.
Identify and implement a data-ingestion solution.
Identify and implement a data-transformation solution.
Opinion: IMHO this domain should be reduced to 15% or even 10%. I found the questions pretty repetitive, and they were about Big Data, not about Machine Learning. If you’ve already passed the Big Data Specialty certification, you’ll be fine. If not, make sure you’re very familiar with Kinesis and its different flavours, or you’ll have a miserable time.

##### Domain 2: Exploratory Data Analysis (24%)
Sanitize and prepare data for modeling.
Perform feature engineering.
Analyze and visualize data for machine learning.
Opinion: typical Data Science stuff, not really tied to any particular AWS service. Cleaning data, handling missing values, performing basic feature engineering. If you have hands-on ML experience, this won’t be a problem at all. Questions don’t go very deep. I was surprised to get a few questions on data viz, most of them pretty vague and awkward to answer without looking at any actual data. IMHO they should be dropped and replaced with more questions on feature engineering.

#### Domain 3: Modeling (36%)
Frame business problems as machine learning problems.
Select the appropriate model(s) for a given machine learning problem.
Train machine learning models.
Perform hyperparameter optimization.
Evaluate machine learning models.
Opinion: a reasonable mix of high-level questions on framing business problems (algo selection, etc.), SageMaker-related questions (built-in algos, HPO, etc.) and Deep Learning questions (CNN, LSTM, regularization, etc.). Again, if you do this for a living and if you’ve spent some time with SageMaker, you should be fine. I didn’t get any complex algorithm question, and none on specific Deep Learning frameworks (TensorFlow, etc.). IMHO, this could be a little more challenging than it is :)

#### Domain 4: Machine Learning Implementation and Operations (20%)
Build machine learning solutions for performance, availability, scalability, resiliency, and fault tolerance.
Recommend and implement the appropriate machine learning services and features for a given problem.
Apply basic AWS security practices to machine learning solutions.
Deploy and operationalize machine learning solutions.



![Alt Text](https://d1.awsstatic.com/training-and-certification/machinelearning/path_ml-exam-preparation.0849ffc65449f465503b5d3b92410677a2ca62b3.png)

-----------------------

- AWS Sagemaker Developer Guide 
- https://docs.aws.amazon.com/sagemaker/latest/dg/whatis.htmlWong 

- Tai Sin's recommended Sagemaker build-in9 big algorithm video

- Learning Path and AWS university from AWS's official website:
- https://aws.amazon.com/training/learning-paths/machine-learning/exam-preparation/

----------------------------
## Machin learning


![Alt Text](https://www.sparkmythought.com/wp-content/uploads/2019/04/machine-learning-hierarchy.jpg)


![Alt Text](https://miro.medium.com/max/1252/1*KFQI59Yv7m1f3fwG68KSEA.jpeg)

![Alt Text](https://www.mindmeister.com/export/image/969402186?height=600&t=MITG7ZIKaz&variable_size=1&width=1200)

- https://robchavez.github.io/datascience_gallery/html_only/machine_learning_basics.html


 #### Model parameter :
   Parameters are those which would be learned by the machine like Weights and Biases.
 
 #### Hyperparameter :  
 Hyper-parameters are those which we supply to the model, for example: number of hidden Nodes and Layers,input features, Learning Rate, Activation Function etc in Neural Network,
 
##### Diffrence between model param vs HyperParam
- https://machinelearningmastery.com/difference-between-a-parameter-and-a-hyperparameter/
 
 
 #### Learning Rate : 
 Determines the size of the step taken during gradient descent optimization ,Between 0 and 1
 
 #### Batch Size :
 -  The number of sample used to train at any one time.
 -  Could be all one or some of your data (batch ,stochastic ,or mini-batch)
 -  Often 32 ,64 and 128 
 -  Calculable from infrastructure
 
 #### Epoches :
-  The number of times that the algorithm will process the entire  training data.
- Each epoch contains one or more batches
- Each epoch should see the model get closer to the desired state
- Usually a high number :
- 10,100,1000 and up

#### What is the Difference Between a Batch and an Epoch in a Neural Network?

- https://machinelearningmastery.com/difference-between-a-batch-and-an-epoch/
 
-----------------------------
- https://github.com/vaquarkhan/amazon-sagemaker-examples
- https://aws.amazon.com/training/learning-paths/machine-learning/exam-preparation/
- https://github.com/vaquarkhan/Effective-Amazon-Machine-Learning
- https://noahgift.github.io/aws-ml-guide/lessons/Lesson1_AWSML_Overview.html
- https://www.linkedin.com/pulse/my-take-aws-certified-machine-learning-speciality-beta-kalyan-janaki/
- http://getyouralgorithm.blogspot.com/2018/01/study-based-exam-notes-and-study-plan.html
- https://www.linkedin.com/pulse/how-prep-pass-aws-machine-learning-specialty-austin-tidmore/
- https://www.youtube.com/playlist?list=PLEF5xKHm-3ZNDvdJpMCLu9xa1oDNvAmMr
- https://colab.research.google.com/github/noahgift/aws-ml-guide/blob/master/Lesson1_AWSML_Overview.ipynb
- https://medium.com/@julsimon/thoughts-on-the-beta-machine-learning-certification-869a5a469597
- https://www.linkedin.com/pulse/aws-certified-machine-learning-specialty-some-thoughts-david-gu/
- https://www.cloudreach.com/en/insights/blog/aws-certified-machine-learning-speciality-exam-resources-and-tips/
