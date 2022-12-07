# Stem-Assignment--Minghao-Liang

Description of Stem assignments

1 Assignment 1 
1.1	Question 1
1.1.1	Use the sorted () function 
•	All the dataset has been sorted. We can find the newest and oldest datasets in the new dataset. 
•	Then print the last column in the newest and oldest datasets. 
•	Use the display (IMG ()) function to display the oldest and the newest images. 

1.1.2	Use the sorted () function 
•	Use the np.argmax () function to find the biggest value in the numpy array.
•	Use the np.argmin () function to find the smallest value in the numpy array.
•	Find the last column of the biggest and the smallest values
•	Use the display (IMG ()) function to display the oldest and the newest images. 

1.2	Question 2
1.2.1 Create the volumes of each object
•	Define the length, width and height of the dataset.
•	Area= length*width
Volume=area*height
Use the np.multiply() function to multiply values

1.2.2 Calculate the 20% of the volume
•	Sort the volume and use the len() function to calculate the length of the volume 
•	Then calculate the volume*0.2
•	Find the values from volume*0.2 to -volume*0.2-1

1.2.3 Plot a histogram of the remaining object's volumes
•	Define the data from the interval and put it into plt.hist()
•	Chose the title, xlabel and ylabel, then use the plt.show() function to draw the histogram. 

1.3	Question 3
1.3.1 What are the most common category and group? 
•	Find the category and group column from the dataset
•	Find the mode of the category and group
•	Calculate the number of occurrences 
1.3.2 What percentage of the total items to they each make up?
percentage= occurrences of the most common category / the total category * 100%

1.4	Question 4
1.4.1	Plot date of objects against width from everything added to the collection between 1850 and 1900.
•	sort the dataset and find the date of objects between 1850 and 1900
•	width, begindate and from everything added to the collection between 1850 and 1900 

1.4.2	If you can put in a legend mapping material to colour.
•	use the mode to find all the materials
•	then use the filter function to find the width of each material 
•	Set the x-axis/y-axis for each material
•	Solution1 use the plt.pot to draw---put all data into the function 
•	Solution2---use the histogram to draw--- define the different colours for the different materials, define the histogram and then plt.show()

1.4.3	Write a short paragraph describing what the plot tells about the museums collection in relation to time, width and material. 


2	Assignment 2
2.1 We want to save the onsets as we go (the sample location and the value) and then plot them on the same plot as the original waveform

•	Use the librosa.load() to read audio
•	Create the empty []
•	Define the start and the end of the window
•	Define the size of the window
•	Find the mean of the whole audio and use the abs() to make the result to be positive numbers
•	Create the if function to make the sample to be the maximum of the window, sample more than the mean of all audio and time less than 0
•	Append the results to the empty[], and time1 reduce 1
•	Define the x-axis and y-axis
•	Plot audio file
•	Plot all the onsets time

2.2 Experiment with different settings for your onset detector.

•	Decrease the window size, and the results increase. 
•	Increase wait time and the results decrease. 
•	Write a short discussion on the advantages and disadvantages of changing the window size and wait time. 


3	Assignment 3
•	Create an experimental programme to research if virtual environments improve human positivity for movement in confined spaces. 
•	The conditions (confined space with or without screens) have been set. 
•	Location of participants' hands based on motion capture gloves to record the data. 
•	Discuss confounding variables and experimental errors, internal and external validity and some ethical issues. 
![image](https://user-images.githubusercontent.com/119888223/206171233-6df06df5-86e4-48cd-83d7-33bf0532e944.png)
