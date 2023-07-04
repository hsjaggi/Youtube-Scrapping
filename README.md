# Youtube-Scrapping

I started this project by first creating an YouTube API Key which will be our credential to access youtube data. 
I will add the instructions on how to create an API Key. 

Once the API Key is generated, I will then use this API key to access different youtube data. I.e. I will walk through the 
documentation given by google to use youtube API. I will look at the different sections in the documentation to access different data I 
need to build this project. I will also look at the sample python code given by google to call different resources and methods to fetch 
youtube data.

Finally, I will get into writing the python code to build this project. I will be using Jupyter Lab(notebook) to write my python code. Since it 
is a new project, I will create a new virtual environment for this project. I will use anaconda for this. Once the virtual environment is set, 
I will then install all the required python packages. So I will install "google-api-python-client" (which is the google python package required 
to access youtube api data), I will also install pandas and seaborn. 

Once the environment is set and required packages are installed, I will then start writing the code in Jupyter Notebook. I have divided this 
project into 2 parts.

In the first part, I extracted channel details from youtube. I.e. I extract details such as youtube channel name, total no of subscribers, 
total views and total number of videos posted by each channel. I gather these details for few Data Analyst/Data Scientist kind of channel and 
then compare these channel data with each other. I shall see who has the highest subscriber and who gets the most views and the amount of videos 
posted by these channels. I will be loading all of this data into a pandas dataframe and then analyze it. I will also generate some basic 
visualization using this data so I can easily compare these multiple channels.

In the second part of the video, I shall build a logic to extract video details from a particular channel. I shall extract details such as 
video title, total views each video has got, total number of likes, and comments each video has got. I shall extract these details 
for all of the videos posted by a particular channel. I will then analyze this data by loading it into a pandas dataframe. At the end I will 
create some simple visualization using Seaborn python library.
