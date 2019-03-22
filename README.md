# Open Payments Model

Data : https://www.cms.gov/OpenPayments/Explore-the-Data/Dataset-Downloads.html

Model the paper *Predicting Unethical Physician Behavior At Scale: A Distributed Computing Framework*

Paper authors: Miguel Romero, Robert Sandor, Diane Myung-kyung Woodbridge, Paul Intrevado, and Anastasia Quinn Keck (me) as part of the Data Science Program at the University of San Francisco

Using Amazon EC2 and EMR, MongoDB, and Spark MLlib we explore 28.5 gigabytes of CMS Open Payments data in an attempt to identify physicians who may have a high propensity to act unethically, owing to significant transfers of wealth from medical companies. This Random Forest Classifier is employed to predict the top decile of physicians who have the highest risk of unethical behavior in the following year, resulting in an F-Score of 91%.

