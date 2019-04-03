# Dataproject

The data used in this project is a random sample of sales in Copenhagen for the year 2005 without missing values. The data is imported from a statafile and contains the following variables: number of rooms, floor, toilets, location, m2, price and age. Furthermore, data is divided into four different sub-areas KBH K, KBH N, KBH V and KBH OE by the variable location. The dataset is subset by dropping the variable “building-units”, which contains the number of apartments in the different buildings. Potential outliers are also removed from the dataset. Dummy-variable for the different sub-areas within Copenhagen is created to visualize the distribution of the variable “price”.
 
Theory sections are excluded in this paper, as the main focus is learning Python, its applications and writing code. The aim of this paper is to give a simple understanding of the dependency between the variables within the real estate market in Copenhagen, by using simple supervised learning. 

The code is written in a chronological order, so you run the code sequentially (from top to bottom). The first section of the code is importing, cleaning, creating new variables in the dataset. The second section is visualizing of the data and correlation plots. The third section is supervised learning where the approach is regression analysis.
