<h1 align="center" >Cyber-Vyuh</h1>

<h2 align="" >About the Project</h2>
The project uses the NSL-KDD Dataset from Kaggle to create 
machine learning models that allow the intrusion detection in networks based on the Internet traffic info.The dataset was downloaded from Kaggle. 
Here is the  <a href="https://www.kaggle.com/datasets/hassan06/nslkdd" >link</a> to the dataset.

<h2 align="" >Setup</h2>

To run the notebook one can either prefer using Google Colab the better method or run the notebook locally.

For running the notebook locally, follow the steps [Windows]:

1. Clone the repository using `git clone https://github.com/Namratha2301/IntrusionDetection.git`
2. Set directory to cloned repo `cd IntrusionDetection`
3. Create a python virtual environment for the project using `python -m venv env`
4. Activate the environment using `env\Scripts\activate`
5. Install the dependencies using `pip install -r requirements.txt`
6. Open the Jupyter Notebook IDE using `jupyter notebook`
7. The Jupyter Notebook IDE should open up allowing you to run the file

<h2 align="" >Machine Learning Models and Scores</h2>
<table align="center" >
<thead>
<th>S.No</th>
<th>Model</th>
<th>Package</th>
<th>Score</th>
</thead>

<tr>
<td>
1
</td>
<td>
Random Forest 
</td>
<td>
SciKit-Learn
</td>
<td>
99.5%
</td>
</tr>

<tr>
<td>
2
</td>
<td>
Support Vector Machine
</td>
<td>
SciKit-Learn
</td>
<td>
98.2%
</td>
</tr>

<tr>
<td>
3
</td>
<td>
Logistic Regression 
</td>
<td>
SciKit-Learn
</td>
<td>
93.7%
</td>
</tr>

<tr>
<td>
4
</td>
<td>
Gaussian Naive Bayes
</td>
<td>
SciKit-Learn
</td>
<td>
88%
</td>
</tr>

<tr>
<td>
5
</td>
<td>
Gradient Boosting
</td>
<td>
SciKit-Learn
</td>
<td>
99.1%
</td>
</tr>

<tr>
<td>
6
</td>
<td>
Multi-Layer Perceptron
</td>
<td>
SciKit-Learn
</td>
<td>
99.2%
</td>
</tr>

<tr>
<td>
7
</td>
<td>
Decision Tree
</td>
<td>
SciKit-Learn
</td>
<td>
92.4%
</td>
</tr>
</table>



