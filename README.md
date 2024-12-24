For More, Check out the Documentation.

Sentiment analysis, often known as opinion mining, is the process of categorizing textual data as positive, negative, or neutral (Liu, 2012) This approach is commonly utilized in areas such as market research, consumer feedback, and social media monitoring (Pang, 2008). The purpose of this research was to categorize textual data into predetermined sentiment categories such as positive and negative, allowing for a better comprehension of the data's emotional associations.

Dataset Description and Exploratory Data Analysis
The dataset 'Time Goes By blog posts and comments (up to 08/2016)' was obtained from the Harvard Dataverse website. It included 4,151 blog articles from an older adult activist's https://www.timegoesby.net/ blog, including the post date, title, URL, commentators, and comments up to August 2016.

Exploratory Data Analysis
The first step was to import the essential libraries. The dataset was loaded from a CSV file using the open function in read-only mode (r), utf-8 encoding, and errors='ignore' to manage encoding difficulties. The read method saved the file's content as a single string to raw_data for further processing. 
