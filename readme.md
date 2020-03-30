# Challenge

# Data Processesing
I initially used LabelEncoder (sklearn.preprocessing) to re-lable the string columns to numeric, but this lead to a smooth elbow curve (K= 6 ,7, or 8). I then used get_dummies (pandas) to convert the same column and this lead to a much clearer elbow curve (K = 4 or 5).

# K-Means
I had the choice between K = 4 or 5. I chose 4 because of the 3D plot. The 3D plot with K = 4, had classes 0 and 2 split more logically.

With K = 4, class 0 was contrained to lower "PC 2" values. When K = 5 there was a less clear way to define the 3 different classes near the origin. 

# Scatter Plot 1
![3D Scatter Plot](https://github.com/Calistic/Cryptocurrencies/blob/master/pics/3d.PNG)

# Data Table
![Table](https://github.com/Calistic/Cryptocurrencies/blob/master/pics/table.PNG)

# Scatter Plot 2
![2D Scatter Plot](https://github.com/Calistic/Cryptocurrencies/blob/master/pics/2d.PNG)