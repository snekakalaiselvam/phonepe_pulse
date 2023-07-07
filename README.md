# phonepe_pulse Data Visualization and Exploration : A User-Friendly Tool Using Streamlit and Plotly 
# About PhonePe Pulse:
BENGALURU, India, On Sept. 3, 2021 PhonePe, India's leading fintech platform, announced the launch of PhonePe Pulse, India's first interactive website with data, insights and trends on digital payments in the country. The PhonePe Pulse website showcases more than 2000+ Crore transactions by consumers on an interactive map of India. With over 45% market share, PhonePe's data is representative of the country's digital payment habits.
The insights on the website and in the report have been drawn from two key sources - the entirety of PhonePe's transaction data combined with merchant and customer interviews. The report is available as a free download on the PhonePe Pulse website and GitHub.
# Libraries needed for the project!
Plotly - (To plot and visualize the data)
Pandas - (To Create a DataFrame with the scraped data)
mysql.connector - (To store and retrieve the data)
Streamlit - (To Create Graphical user Interface)
json - (To load the json files)
git.repo.base - (To clone the GitHub repository)
# codeflow
# Step 1:
# Importing the Libraries:
Importing the libraries. As I have already mentioned above the list of libraries/modules needed for the project. First we have to import all those libraries.
# Data extraction:
Clone the Github using scripting to fetch the data from the Phonepe pulse Github repository and store it in a suitable format such as JSON.
# Step 3:
# Data transformation:
In this step the JSON files that are available in the folders are converted into the readeable and understandable DataFrame format by using the for loop and iterating file by file and then finally the DataFrame is created. In order to perform this step I've used os, json and pandas packages. And finally converted the dataframe into CSV file and storing in the local drive.
# Step 4:
# Database insertion:
To insert the datadrame into SQL first I've created a new database and tables using "mysql-connector-python" library in Python to connect to a MySQL database and insert the transformed data using SQL commands.
# Step 5:
# Dashboard creation:
To create colourful and insightful dashboard I've used Plotly libraries in Python to create an interactive and visually appealing dashboard. Plotly's built-in Pie, Bar, Geo map functions are used to display the data on a charts and map and Streamlit is used to create a user-friendly interface with multiple dropdown options for users to select different facts and figures to display.
# Step 6:
# Data retrieval:
Finally if needed Using the "mysql-connector-python" library to connect to the MySQL database and fetch the data into a Pandas dataframe.
