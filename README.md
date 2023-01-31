# Visualization-challenge- Pymaceuticals (Anti-cancer medications Analysis)

# Purpose
The purpose of this study is to compare the performance of the Pymaceuticals drug "Capomulin" against other treatments regimens, generate tables and figures needed for the technical report and clinical study, and also summurize the study result.

# Tools
Jupyter notebook, Python, Matplotlib, Pandas, Scipy

# Instruction
* Prepare the data using the provided package dependency and data imports, merge the mouse_metadata and study_reults DataFrames into a single DataFrame. Display the number of unique mice IDs and check for any mouse ID with duplicate time points. Remove the duplicate and create a new Dataframe. Display the updated number of unique mice ID.
* Generate summary statistics that shows a row for each drug regimen and a column for each of the following statistics: mean, median, variance, standard deviation, and SEM of the tumor volume.
* Create bar charts and pie charts using both Panda DataFrame.plot() and Matplotlib pyplot to show total number of time points for all mice tested for each drug regimen throughout the study and distrbution of female versus male mice in the study.
* Calculate quartiles, find outliers of each mouse across four of the most promising treatment regimens ( Capomulin, Ramicane, Infubinol, Ceftamin)and use Matplot to generate a box plot that shows final distribution of final tumor volume for all mice in each treatment group.
* Create a line plot  for a mouse treated with Capomulin to display tumor volume versus time point, and  genrate a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.
* Calculate the correlation coefficient and linear regression model between mouse weight and a average tumor volume for the Capomulin treatment, and plot linear regression model on top of the previous scatter plot.

# Results
The results/ graphs should look like the followings:

Mouse ID with duplicate time points
![Mouse ID with duplicate time points](https://user-images.githubusercontent.com/115572537/215768342-3a91b2f8-59f0-4aac-a702-c8c8121f8b34.png)

Summary statistics
![Summary Statistics (2)](https://user-images.githubusercontent.com/115572537/215772025-66aff4dd-6045-4c76-9367-533a02fd1f29.png)

Statistics by aggregation method
![Aggregation method (2)](https://user-images.githubusercontent.com/115572537/215768999-3393eb80-109b-4d81-9526-c3b7e3eac202.png)

Bar charts 
![Bar chart(Pandas)](https://user-images.githubusercontent.com/115572537/215769096-871f6a59-522b-481c-8279-2913b0352583.png)

![Bar chart(Pyplot)](https://user-images.githubusercontent.com/115572537/215769181-9b21db2f-201d-4f9d-b1eb-0b0005a8c768.png)

Pie chart showing distribution of female vs. male mice
![Pie chart(Pandas)](https://user-images.githubusercontent.com/115572537/215769803-a56c35ca-b207-4dd3-8544-a5ebc6b914b7.png)
![Pie chart(Pyplot)](https://user-images.githubusercontent.com/115572537/215769888-5056a66c-cced-49ed-840d-bad5e20d1fbd.png)

Box plot
![Box plot](https://user-images.githubusercontent.com/115572537/215770394-ff2a739e-0da4-4f44-9e9f-321c291291d8.png)

Line plot
![Line plot](https://user-images.githubusercontent.com/115572537/215770559-46a63ab1-9855-4a18-97df-ed3e1ffbfe2f.png)

Scatter plot
![Scatter plot](https://user-images.githubusercontent.com/115572537/215770966-ad1a9998-926f-4416-9c58-5f484a4948ce.png)

Linear regression model
![Linear regression](https://user-images.githubusercontent.com/115572537/215771030-70d1cfe9-de04-4623-950a-0fc8f7b79cb1.png)

# Reference
(2020). A. Sweigart, Automate Boring Stuff with Python 2ND Edition: Practical Programming for Total Beginners, San Francisco CA: No Starch Press, Inc

Keith Galli,(2019, Jun 1). Intro to Data Visualization in Python with Matplolib!(Line graph, Bar chart, Title, Labels, Size). Retrived from https://youtu.be/DAQNHzOcO5A

Jason Lepelmeier,(2023, Jan 26). Class lecture: Power point slides 5.3 Introduction to Statistics. Data Analytics and Visualization Bootcamp. University of Minnesota.https://umn.bootcampcontent.com/University-of-Minnesota-Boot-Camp/UofM-VIRT-DATA-PT-12-2022-U-LOLC/-/tree/main/Data-Visualization/5.3
