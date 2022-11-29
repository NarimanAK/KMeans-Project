# KMeans-Project
Creating Cluster model using K-Means method
Lithion Power is the largest producer of electric vehicle batteries. They provide batteries on rent to e-vehicle drivers. Drivers rent a battery typically for a day and, after that, replace it with a charged battery from the company. This indicates that Lithion Power has a variable pricing model based on the driver's driving history. Battery life depends on factors such as speeding, distance driven per day, etc. 

I created a cluster model using the K-Means cluster method. Drivers can be grouped based on the driving data and group the data points so drivers will be incentivized based on cluster. I standardized the data points with the StandardScaler() function before implementing the KMeans method. Moreover, I used the Elbow Method to find the optimal value of k in KMeans, which turns out to be k=4. 
