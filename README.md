CHAPTER - I
INTRODUCTION
       In the contemporary landscape of marketing, understanding the dynamics of campaign performance is paramount for achieving business success. The Marketing Campaign Performance Dataset stands as a reservoir of invaluable insights, offering a comprehensive analysis of the efficacy of diverse marketing campaigns. Spanning a period of two years and comprising 200,000 unique entries, this dataset encapsulates a wealth of data points crucial for unravelling the intricacies of marketing initiatives.
       At its core, this dataset captures a myriad of performance metrics, ranging from conversion rates to engagement levels, providing a holistic view of campaign effectiveness. Moreover, it delves into the specifics of target audience segmentation, campaign durations, and the channels utilized, shedding light on the factors that drive the success of marketing endeavours.
       In this project, we embark on a journey to dissect and analyze this extensive dataset, aiming to extract actionable insights that can inform and enhance future marketing strategies. By leveraging advanced analytics and data science techniques, we seek to uncover patterns, trends, and ultimately empowering organizations to make informed decisions and optimize their marketing efforts.
Through meticulous exploration and analysis of this dataset, we endeavour to address key questions such as:
•	What are the most effective channels for reaching different customer segments?
•	What are the characteristics of campaigns that yield high conversion rates?
•	How do varying target audience influence campaign success metrics?
       By unravelling the intricacies of marketing campaign performance through data-driven exploration, this project aims to provide valuable insights like getting the reach and exposure rate of their campaign, engagement rate of their target audience towards their campaign, conversion rate of their target audience towards their campaign and these factors can drive strategic decision-making and propel organizations towards marketing excellence in a dynamic and competitive landscape.


CHAPTER – II
BUSINESS UNDERSTADING
       In today's rapidly evolving digital landscape, businesses are continuously challenged to navigate through a myriad of marketing channels and strategies to effectively reach and engage with their target audience. Marketing campaigns serve as crucial vehicles for businesses to convey their brand message, promote products or services, and ultimately drive desired actions from consumers. However, with the proliferation of digital platforms and technologies, the landscape of marketing campaign performance analysis has become increasingly complex yet essential for businesses to thrive in the competitive marketplace.
EVOLUTION OF MARKETING CAMPAIGNS IN THE DIGITAL ERA
       The digital era has revolutionized the way businesses conceptualize, execute, and measure marketing campaigns. Traditional marketing channels such as print media, television, and radio have been supplemented, and in many cases, replaced by digital channels including social media, search engines, email, and mobile applications. This shift has not only broadened the reach of marketing campaigns but has also provided businesses with unprecedented access to consumer data and insights.
        Marketing campaigns in the digital era are characterized by their agility, interactivity, and measurability. Unlike traditional campaigns that often rely on subjective metrics such as brand awareness and impressions, digital campaigns can be precisely tracked, monitored, and optimized in real-time. This ability to gather and analyze data has transformed the way businesses understand and evaluate the performance of their marketing efforts.
IMPORTANCE OF MARKETING CAMPAIGN PERFORMANCE ANALYSIS
Analyzing the performance of marketing campaigns is essential for several reasons:
•	Optimizing Resource Allocation: Marketing budgets are finite, and businesses need to allocate resources effectively to maximize ROI. By analyzing campaign performance, businesses can identify which channels, messages, and tactics are delivering the best results and allocate resources accordingly.
•	Improving Campaign Effectiveness: Understanding what works and what doesn't is crucial for improving the effectiveness of future marketing campaigns. By analyzing performance metrics, businesses can identify areas for improvement, test new strategies, and refine their approach to better resonate with their target audience.
•	Measuring ROI: Ultimately, businesses invest in marketing campaigns with the expectation of generating a positive return on investment. By tracking key metrics such as conversion rates, customer acquisition costs, and revenue generated, businesses can measure the ROI of their marketing efforts and justify their marketing spend.
•	Informing Strategic Decision-Making: Marketing campaign performance analysis provides valuable insights that can inform strategic decision-making at both the tactical and strategic levels. Whether it's launching a new product, entering a new market, or repositioning a brand, data-driven insights can help businesses make informed decisions that drive growth and profitability.
•	Staying Competitive: In today's hyper-competitive marketplace, businesses must continuously innovate and adapt their marketing strategies to stay ahead of the competition. By monitoring and analyzing campaign performance, businesses can identify emerging trends, benchmark against competitors, and capitalize on opportunities to gain a competitive advantage.
Data Sources for Marketing Campaign Performance Analysis
In the digital age, companies have access to a wealth of data sources for analyzing campaign performance:
•	Web Analytics: Platforms like Google Analytics provide insights into website traffic, user behaviour, and conversion metrics, allowing companies to track the performance of digital campaigns.
•	Social Media Analytics: Social media platforms offer analytics tools that provide data on audience demographics, engagement metrics, and campaign performance across various social channels.
•	Email Marketing Platforms: Email marketing services provide data on open rates, click-through rates, and conversion metrics for email campaigns, enabling companies to measure the effectiveness of their email marketing efforts.
•	Advertising Platforms: Platforms like Google Ads and Facebook Ads offer data on ad impressions, clicks, conversions, and ROI for paid advertising campaigns, helping companies optimize their advertising spend.
       Marketing campaign performance analysis is essential for businesses to evaluate the success of their marketing initiatives, optimize strategies, and drive business growth. By leveraging data-driven insights, organizations can make informed decisions, allocate resources effectively, and stay competitive in today's digital marketplace. However, to reap the benefits of performance analysis, businesses must overcome challenges related to data fragmentation, quality, attribution, privacy, and resource constraints. By following best practices and investing in analytics tools and technologies, organizations can unlock the full potential of their marketing campaigns and achieve sustainable success in the digital age.
 
TOOL USED
PYTHON
      Python stands out as a highly versatile programming language, renowned for its simplicity, flexibility, and expansive ecosystem of libraries and frameworks. Widely embraced in the data science community, Python's robust support for data manipulation, analysis, and visualization has solidified its position as a go-to language for professionals in the field. Notable libraries like Pandas, NumPy, Matplotlib, and Seaborn empower users with efficient tools for data processing, statistical analysis, and graphical visualization, enhancing the overall data exploration experience.
       Furthermore, Python seamlessly integrates with machine learning libraries such as Scikit-learn, TensorFlow, and PyTorch, facilitating intricate tasks like regression, classification, clustering, and neural network implementations. Python's user-friendly syntax and scalability make it an ideal choice across the spectrum of data analytics projects, from initial exploratory data analysis to the complexities of advanced predictive modelling.
TABLEAU
       Tableau is extensively used in Exploratory Data Analysis (EDA) due to its user-friendly interface and powerful visualization capabilities. It allows users to easily explore and analyze data before diving into more complex tasks like machine learning models. EDA is crucial as it provides valuable insights into the data, helps identify outliers, and aids in understanding the relationships between variables.
       Tableau simplifies EDA by offering features like creating histograms, box plots, scatter plots, and dashboards. In univariate analysis, Tableau enables users to visualize one variable at a time, understand its distribution, mean, median, and variance using tools like histograms and box plots. For bivariate analysis, Tableau facilitates the analysis of two variables to determine their empirical relationship through scatter plots.
        Moreover, Tableau allows for the creation of dashboards to consolidate various visualizations, making it easier to interpret and derive insights from the data. By using Tableau in EDA, analysts can efficiently clean data, perform univariate and bivariate analysis, and prepare the data for further modelling and decision-making processes.
        Overall, Tableau's role in EDA is significant as it streamlines the process, enhances data exploration, and empowers users to gain a deeper understanding of their datasets through intuitive visualizations and analysis tools


CHAPTER - III
DATA UNDERSTANDING
Understanding campaign effectiveness is no longer a luxury, it's a necessity. Marketers crave insights that illuminate what works, what flops, and why. This is where the Marketing Campaign Performance Dataset emerges as a game-changer.
      This comprehensive resource, boasting 200,000 unique data points spanning two years, offers an unparalleled window into the inner workings of marketing campaigns across various industries and customer segments. By delving into the core elements captured within this dataset, we can embark on a journey of discovery, unearthing valuable knowledge to optimize our marketing strategies and achieve unparalleled results.
•	Performance Metrics: This is the heart of the dataset, the quantifiable measures that define a campaign's success. We can expect to find metrics like:
o	Conversions: The number of desired actions taken by the target audience, such as purchases, sign-ups, or website visits.
o	Click-through Rate (CTR): The percentage of people who clicked on a marketing message compared to those who saw it.
o	Cost-per-Acquisition (CPA): The cost associated with acquiring a new customer through the campaign.
o	Return on Investment (ROI): The net profit or loss generated by the campaign.
o	Impression Share: The percentage of times your ad was shown compared to the total number of times it could have been shown.
•	Target Audience: Understanding who you're targeting is fundamental. This section likely details demographics like age, location, interests, and online behaviour, enabling us to tailor messaging and channels for maximum impact.
•	Campaign Duration: The timeframe over which the campaign ran provides context for analysing performance. We can assess the effectiveness of short bursts versus long-term campaigns and identify trends over time.
•	Marketing Channels: The dataset likely categorizes the communication channels used, such as social media marketing, email marketing, search engine marketing (SEM), content marketing, and influencer marketing. Analyzing channel performance allows us to identify the most effective avenues for reaching our target audience.
CHANNELS USED
EMAIL:
       Marketing by email is a great way to keep your business top-of-mind with customers and prospects so they don't think of your competitors. When done correctly, your email marketing campaign can show great success and lead customers to act, which is what all businesses want when developing their campaigns.
SOCIAL MEDIA PLATFORMS:
        Social media platforms provide a powerful channel for reaching and engaging with a large audience, which can help increase brand awareness and recognition. Engaging with customers through social media channels can help build stronger relationships and foster customer loyalty.
YOUTUBE:
        YouTube marketing is a strategy that involves creating videos and uploading them on YouTube to promote a brand or a product and gain more exposure. It helps companies boost traffic, increase their customer base, and reach new audiences.
INSTAGRAM:
        Instagram marketing is a type of social media marketing, which involves promoting a brand on Instagram. This social media platform helps brands connect with an enormous audience, increase brand awareness, and boost sales.
WEBSITE:
        A website is the central platform for all digital marketing activities that take place online. It is a powerful channel on its own and can be used to execute various online marketing campaigns. A website needs to represent a brand, product, or service in a memorable and easy-to-understand way.
FACEBOOK:
        Facebook marketing is the strategic promotion of a business or brand using the Facebook platform. Facebook marketing can enhance brand recognition, expand your online audience, capture potential leads, and boost sales of products or services.



CAMPAIGN USED
INFLUENCER
        Leveraging influencers can boost brand awareness, drive conversions, and provide a cost-effective strategy for reaching target audiences.
EMAIL:
        Marketing by email is a great way to keep your business top-of-mind with customers and prospects so they don't think of your competitors. When done correctly, your email marketing campaign can show great success and lead customers to act, which is what all businesses want when developing their campaigns.
DISPLAY:
        Display advertising can be a valuable tool for businesses to enhance their marketing efforts and achieve their goals. By using visually appealing ads across various digital platforms, businesses can increase brand awareness, target specific customer segments, and measure campaign performance.
SEARCH
      Paid search provides marketers with valuable data insights that can help shape their overall marketing strategy, such as what keywords and ad copy are resonating with their target audience, the times of the day their ads perform best, and which days of the week users are most likely to click on ads.
SOCIAL MEDIA
       By sharing engaging content, businesses can create a strong online presence and establish themselves as industry leaders.





•	In the above picture, it shows the dataset in the Microsoft excel format and the columns that are present inside the data. 








•	In the above picture “df.shape” command has been used to identify rows and columns present in the dataset, it shows us there are “200000” rows and “16” columns are present in the dataset.
•	“df.info” command has been used to identify the “Data type”, “Non-null” and “Count”.
•	This dataset consists of three dtype: float64, int64, object.
•	Conversion rate and ROI are float64 dtype. 
•	Campaign ID, Clicks, Impressions and Engagement Score are int64 dtype.
•	Company, campaign type, target audience, duration, channel used, acquisition cost, location, language, customer segment, and date are all the columns which have object dtype. 
•	All the columns are having the total 200000 values and non-null count in their respective columns.
•	The “df.info” is also showing the memory usage or size of the dataset.
•	It shows us the range index of the dataset “0” to “199999”.
 


•	In the above picture “df.columns” command have been used, it shows us the name of the columns that are present in the dataset.
•	In this dataset there are 16 columns they are Campaign ID, Company, Campaign Type, Target Audience, Duration, Channel Used, Conversion Rate, Acquisition Cost, ROI, Location, Language, Clicks, Impressions, Engagement Score, Customer Segment and Date.
•	The Other Command is “df.head” command where it shows us the first five data of the dataset from “0” to “4”.

 


•	In the above the picture “df.tail” command has been used, Where it shows us the last five data of the dataset from “199995” to “199999”.
•	The Other command is “df[‘Channel Used’].unique()” this command is used for showing us each data that is present in the columns. For example, “channel used” in this specific column there are 6 different data are here “Google ads, YouTube, Instagram, Website, Facebook, Email”.
 
       In this picture “df[‘Channel Used’].value_counts() command is used for showing us how many values that each specified data is consisting in it. For example, “channel used” column is taken here, Where Email has 33599 values, Google Ads have 33438 values, YouTube and Instagram has 33392 values, Website has 33360 values, Facebook has 32819 values.
 
CHAPTER - IV
DATA PREPARATION
        Data preparation, also known as data preprocessing, is a crucial step in the data analysis process where raw data is transformed, cleaned, and organized to make it suitable for analysis. It involves several tasks aimed at improving the quality of the data and making it more suitable for analysis of machine learning algorithms or statistical models. Some common steps involved in data preparation include:

•	Data Cleaning: This involves identifying and correcting errors or inconsistencies in the data, such as missing values, duplicate records, outliers, or incorrect data formats. Cleaning ensures that the data is accurate and reliable for analysis.
•	Data Integration: In many cases, data comes from multiple sources, and integrating this data involves combining datasets from different sources into a single, unified dataset. This may involve resolving inconsistencies in naming conventions, data formats, or data structures.
•	Data Transformation: Data transformation involves converting the raw data into a format that is more suitable for analysis. This may include scaling numeric data, encoding categorical variables, normalizing data distributions, or creating derived features.
•	Handling Missing Data: Missing data is a common issue in datasets, and various techniques such as imputation (replacing missing values with estimated values), deletion of missing values, or treating missing values as a separate category can be used to handle missing data appropriately.
•	Data Reduction: In some cases, datasets may be too large or complex to analyze efficiently. Data reduction techniques such as aggregation, sampling, or dimensionality reduction can be used to reduce the size or complexity of the dataset while preserving its essential characteristics.
•	Data Formatting: Ensuring that the data is in the correct format for analysis is essential. This may involve converting dates into a standardized format, ensuring consistency in units of measurement, or converting textual data into a structured format.






IMPORTANCE OF DATA PREPARATION:
       Data preparation lays the foundation for accurate and reliable analysis by addressing several key challenges associated with raw data:
•	Data Quality: Raw data often contains errors, missing values, inconsistencies, and outliers, which can adversely affect analysis outcomes. Data preparation involves identifying and rectifying these issues to ensure data quality.
•	Data Integration: In many cases, data comes from multiple sources with varying formats, structures, and semantics. Data preparation involves integrating disparate data sources into a unified format suitable for analysis.
•	Data Relevance: Raw data may contain irrelevant or redundant information that adds noise to the analysis. Data preparation involves selecting and filtering relevant data attributes to focus on the factors that truly impact the analysis.
•	Data Consistency: Ensuring consistency across data attributes is essential for meaningful analysis. Data preparation involves standardizing data formats, units, and terminology to maintain consistency.
•	Data Exploration: Clean and well-prepared data facilitates effective data exploration, allowing analysts to gain insights and identify patterns more efficiently.


 
•	In the above picture, the “Acquisition cost” variable’s “$” has been removed and it has been converted from “object” type variable to float variable.
 

 
•	In this above picture the variable named “Duration” has been changed from “Object” dtype to “int32” dtype.
•	“Date” named variable has been changed from “Object” dtype to “to_datetime” dtype.

 
•	After changing the dtype of “Acquisition Cost”, “Duration” and “Date” variables, again “df.info()” command is used to check whether these variable’s dtype have been changed or not.
•	Once after changing the dtype, now there are 5 dtype are here 
•	“Campaign ID”, “Clicks”, “Impressions” and “Engagement Score” are “int64” dtype. 
•	“Duration” is “int32” dtype. 
•	“Company”, “Campaign Type”, “Target Audience”, “Channel Used”, “Location”, “Language” and “Customer Segment” are “Object” dtype.
•	“Date” is “Datetime” dtype.
•	“Conversion Rate”, “Acquisition Cost” and “ROI” are “float64” dtype.

 

 
•	In this above picture, “df.isnull().sum()” command has been used to check is there are any null values are present in the dataset.
•	In this dataset there are no null values are here.

 
•	In this above picture, “df.isna().sum()” command has been used to check is there are any missing values are present in the dataset.
•	In this dataset there are no missing values values are here.
 
 

•	In the above picture, “unique()” command has been performed for 6 variables, “Company”, “Campaign Type”, “Target Audience”, “Channel Used”, “Language”, “Customer Segment”.
•	Company variable has five different categories in it, “Innovate Industries”, “NexGen Systems”, “Alpha Innovations”, “Datatech Solutions” and “TechCorp”.
•	Campaign Type variable has five different categories in it, “Email”, “Influencer”, “Display”, “Search” and “Social Media”.
•	Target Audience variable has five different categories in it, “Men 18-24”, “Women 35-44”, “Men 25-34”, “All Ages” and “Women 25-34” 
•	Channels Used variable has six different categories in it, “Google Ads”, “Youtube”, “Instagram”, “Website”, “Facebook” and “Email”.
•	Languages variable has five different categories in it, “Spanish”, “French”, “Mandarin”, “German” and “English”.
•	Customer Segment has five different categories in it, “Health & Wellness”, “Fashionistas”, “Outdoor Adventurers”, “Foodies” and “Tech enthusiasts”.
 

 
•	In the above picture, A column named “EngagedRespnse” has been created from “Engagement Score” by using “lambda” function with certain condition, If the engagement is greater than or equal to 6, then it is considered as “Engaged” and if it is lower than 6 then it is considered as “Not Engaged”.
•	In the above picture, A column named “Engaged” has been created from “EngagedResponse” by using “lambda” function with certain condition, If the engaged response is “Yes” then it is “1” and If the engaged response is “No”.
 
•	In the above picture, it shows the boxplot of “Engagement score” and In the above box plot there are no outliers in the “Engagement score” variable.
 

  
•	In the above picture, it shows the boxplot of “Conversion Rate” and in the above box plot there are no outliers in the “Conversion Rate” variable.
 
CHAPTER – V
EXPLORATORY DATA ANALYSIS
       Exploratory Data Analysis (EDA) is an approach to analyzing datasets to summarize their main characteristics, often employing visual methods. The primary goal of EDA is to understand the data, uncover patterns, detect anomalies, and formulate hypotheses that can lead to further investigation or model development. Key aspects of EDA include:
•	Summary Statistics: Calculating basic statistical measures such as mean, median, mode, variance, standard deviation, etc., to understand the central tendency, dispersion, and shape of the data.
•	Data Visualization: Creating visual representations of the data through plots, histograms, box plots, scatter plots, etc., to reveal patterns, trends, and relationships among variables.
•	Data Cleaning: Identifying and addressing missing values, outliers, duplicates, and other data quality issues that may affect the analysis or modelling process.
•	Feature Engineering: Creating new variables or transforming existing ones to better represent the underlying patterns or improve the performance of predictive models.
•	Dimensionality Reduction: Reducing the number of variables in the dataset while preserving its essential features, often through techniques like principal component analysis (PCA) or t-distributed stochastic neighbour embedding (t-SNE).
•	Hypothesis Testing: Formulating and testing hypotheses about the data using statistical methods to assess the significance of observed patterns or differences.
        
        EDA is typically an iterative process, where insights gained from initial exploration may prompt further data cleaning, visualization, or analysis steps. It serves as a crucial foundation for more advanced statistical modelling and machine learning tasks by helping analysts and data scientists gain a deeper understanding of the data they are working with.


 
CLICK RATE OF LEADS DASHBOARD
 
      In the above dashboard, it shows us the Click rate of leads “Campaign Type”, “Customer Segment”, “Company”, “Target Audience” and “Channel Type” 
•	Click Rate based on Company, There are 5 Companies and performed Bar chart for displaying Click Rate, 2,19,93,300 people have clicked and viewed the campaign of Alpha Innovations, 2,20,41,615 people have clicked and viewed the campaign of DataTech Solutions, 2,18,05,668 people have clicked and viewed the campaign of  Innovative Industries, 2,19,57,338 people have clicked and viewed the campaign of NexGen Systems, and 2,21,66,485 people have clicked and viewed the campaign of TechCorp.
•	Click Rate based on Customer segment, There are 5 segments and performed Bubble chart for displaying Click rate, In Fashionistas 2,18,55,164 people have clicked and viewed the campaign, In Health & Wellness 2,19,53,923 people have clicked and viewed the campaign, In Tech Enthusiasts 2,20,35,992 people have clicked and viewed the campaign, In Outdoor Adventurers 2,20,28,553 people have clicked and viewed the campaign and In Foodies 2,20,80,774 people have clicked and viewed the campaign. 




•	Click Through Rate based on Target Audience, There are 5 Target Audience Age Group and performed Bar chart for displaying click rate, 2,20,51,647 Women from the age of (35-44) have clicked and viewed the campaign, 2,19,65,301 From All Age Group both men and women have clicked and viewed the campaign, 2,20,96,802 Men From age group of (18-24) have clicked and viewed the campaign, 2,20,51,647 Women from age group of (25-34) have clicked and viewed the campaign and 2,20,14,338 Men from the age group of (25-34) have clicked and viewed the campaign.
 
•	Click Through rate based on Campaign type, There are 5 types and performed Bar chart for displaying click through rate, Through Social media 2,19,55,724 have clicked and viewed the campaign, Through Display 2,20,30,979 clicked and viewed the campaign, Through Influencer 2,20,37,657 clicked and viewed the campaign, Through Search 2,20,32,144 clicked and viewed the campaign, and Through Email 2,18,97,902 clicked and viewed the campaign.
•	Click Through rate based on Channel type, There are 6 types and performed Pie chart for displaying Click Through rate, Through Google Ads 1,83,40,807 have clicked and viewed the campaign, Through Website 1,84,14,628 have clicked and viewed the campaign, Through YouTube 1,83,50,407 have clicked and viewed the campaign, Through Instagram 1,83,14,628 have clicked and viewed the campaign, Through Email 1,84,93,963 have clicked and viewed the campaign and Through Facebook 1,80,37,947 have clicked and viewed the campaign. 

 
ENGAGEMENT SCORE DASHBOARD
 
        In the above dashboard, it shows us the Engagement of customers of the following categories “Campaign Type”, “Customer Segment”, “Company”, “Target Audience” and “Channel Type” 
•	Engagement of audience based on the 6 different types of Channels. The Engagement is shown in Bubble chart, Through Google Ads 1,83,710 has participated in their campaign, Through Website 1,83,777 has participated in their campaign, Through YouTube 1,83,153 has participated, Through Instagram 1,83,290 has participated in their campaign, Through Email 1,84,386 has participated in their campaign and Through Facebook 1,80,626 has participated in their campaign.
•	Engagement of the Target audience towards Campaign, The Engaged customers are in 5 different groups and visualized it through Bar chart. Women from the age of  (35-44) 2,17,743 has participated in the campaign, From All Age Group both men and women 2,19,588 has participated in their campaign, Men From age group of (18-24) 2,22,026 has participated in their campaign, Women from the age group of (25-34) 2,19,781 has participated in their campaign and Men from age group of (25-34) 2,19,804 has participated in their campaign. 
•	Engagement Rate of Participants based on their Customer segments. There are 5 segments and visualized ti through bar chart , In Fashionistas 2,18,180 has participated in their campaign, In Health & Wellness 2,18,752 has participated in their campaign, In Tech Enthusiasts 2,20,235 has participated in their campaign, In Outdoor Adventurers 2,20,170 has participated in their campaign and In Foodies 2,21,605 has participated in their campaign. 
 
 
•	Engagement Rate based on Campaign type, There are 5 types of Campaign and visualized it through pie chart for displaying engagement rate, Through Social media 2,18,909 has participated in their campaign, Through Display 2,20,164 has participated in their campaign, Through Influencer 2,20,252 has participated in their campaign, Through Search 2,20,347 has participated in their campaign and Through Email 2,19,270 has participated in their campaign.
•	Engagement Rate of the audience in different companies, there are 5 different companies and visualized it through Bar chart. In Tech Corp Company 2,20,309 has participated in their campaign, In Alpha Innovations 2,20,162 has participated in their campaign, In DataTech Solutions 2,20,123 has participated in their campaign, In NexGen Systems 2,19,634 has participated in their campaign and In innovate industries 2,18,714 has participated in their campaign.
 
CONVERSION RATE DASHBOARD
 
      In the above dashboard, it shows us the Conversion rate of leads “Campaign Type”, “Customer Segment”, “Company”, “Target Audience” and “Channel Type”
•	Conversion Rate of Participants based on their customer segments. There are 5 segments and visualized it through bubble chart, In Fashionistas 3,171.18 has converted in their campaign, In Health & Wellness 3188.85 has converted in their campaign, In Tech Enthusiasts 3218.81 has converted in their campaign, In Outdoor Adventurers 3208.10 has converted in their campaign and In Foodies 3226.99 has converted in their campaign.
•	Conversion Rate of the Target audience towards Campaign, The Conversion of customers in 5 different groups and visualized it through Bar chart. Women from the age of  (35-44) 3,179.01 has converted in their campaign, From All Age Group both men and women 3,200.51 has converted in their campaign, Men From age group of (18-24) 3,230.30 has converted in their campaign, Women from the age group of (25-34) 3,197.00 has converted in their campaign, and Men from age group of (25-34) 3207.11 has converted in their campaign.
•	Conversion Rate based on Campaign type, there are 5 types of Campaign and visualized it through pie chart for displaying conversion rate, through social media 3190.72 has converted in their campaign, Through Display 3202.50 has converted in their campaign, Through Influencer 3226.16 has converted in their campaign, Through Search 3213.40 has converted in their campaign and Through Email 3181.15 has converted in their campaign.
 
•	Conversion Rate of audience based on the 6 different types of Channels. The Conversion Rate is shown in Bar chart, Through Google Ads 2,681.17 has converted in their campaign, Through Website 2,674.90, has converted in their campaign, Through YouTube 2,667.66 has converted in their campaign, Through Instagram 2,667.57 has converted in their campaign, Through Email 2,697.38 has converted in their campaign and Through Facebook 2,625.25 has converted in their campaign.
•	Conversion Rate of the audience in different companies, there are 5 different companies and visualized it through Pie chart. In Tech Corp Company 3,225.27 has converted in their campaign, In Alpha Innovations 3207.44 has converted in their campaign, In DataTech Solutions 3200.51 has converted in their campaign, In NexGen Systems 3188.73 has converted in their campaign and, In innovate industries 3191.98 has converted in their campaign.







CHAPTER-VI
MODEL BUILDING
       In today's data-driven world, organizations across various sectors are leveraging data analysis to derive valuable insights, make informed decisions, and gain a competitive edge. At the heart of data analysis lies model building—a process that involves creating mathematical representations of real-world phenomena to predict outcomes or understand underlying patterns. Effective model building requires a combination of domain expertise, statistical knowledge, and proficiency in data manipulation and programming. This comprehensive guide aims to provide an in-depth understanding of model building in data analysis, covering key concepts, methodologies, and best practices.
UNDERSTANDING MODEL BUILDING
       Model building is the process of constructing mathematical or computational representations of real-world systems, processes, or phenomena. These models aim to capture the underlying relationships between variables and make predictions or facilitate decision-making. In the context of data analysis, models are built using historical data to understand patterns, forecast future outcomes, or gain insights into complex systems.
TYPES OF MODELS
       There are various types of models used in data analysis, each suited to different types of data and analytical objectives:
•	Statistical Models: Statistical models utilize mathematical equations to describe relationships between variables. These models include linear regression, logistic regression, time series analysis, and multivariate analysis techniques.
•	Machine Learning Models: Machine learning models use algorithms to learn patterns from data and make predictions or decisions without explicit programming. Common machine learning algorithms include decision trees, random forests, support vector machines, neural networks, and clustering algorithms.
•	Predictive Models: Predictive models are used to forecast future outcomes based on historical data. These models are essential for tasks such as sales forecasting, demand prediction, risk assessment, and fraud detection.
•	Descriptive Models: Descriptive models aim to summarize and interpret data to gain insights into underlying patterns or relationships. These models include clustering algorithms, principal component analysis (PCA), and factor analysis.

STEPS IN MODEL BUILDING
The process of building a model typically involves several key steps:
•	Problem Definition: Clearly define the problem you are trying to solve and the objectives of the analysis. Understand the context in which the model will be deployed and the specific requirements or constraints.
•	Data Collection and Preprocessing: Gather relevant data from various sources and preprocess it to ensure quality and consistency. This step involves cleaning the data, handling missing values, encoding categorical variables, and normalizing or standardizing numerical features.
•	Exploratory Data Analysis (EDA): Conduct exploratory data analysis to understand the characteristics of the data, identify patterns, detect outliers, and explore relationships between variables. Visualization techniques such as histograms, scatter plots, and heatmaps are commonly used in EDA.
•	Feature Selection and Engineering: Select or engineer features that are most relevant to the problem at hand and discard irrelevant or redundant variables. Feature engineering techniques may involve transforming variables, creating new features, or selecting subsets of features based on statistical methods or domain knowledge.
•	Model Selection: Choose an appropriate modelling technique based on the nature of the data and the analytical objectives. Consider factors such as model interpretability, scalability, performance metrics, and computational resources.
•	Model Training: Split the data into training and testing sets and train the chosen model using the training data. Tune model parameters using techniques such as cross-validation to optimize performance and prevent overfitting.
•	Model Evaluation: Evaluate the performance of the trained model using the testing data and appropriate evaluation metrics. Common evaluation metrics include accuracy, precision, recall, F1-score, mean squared error (MSE), and area under the receiver operating characteristic curve (AUC-ROC).
•	Model Deployment and Monitoring: Deploy the trained model into production environments and monitor its performance over time. Continuously update the model as new data becomes available and retrain it periodically to ensure optimal performance.



 
•	In the above picture shows us that, creating a new dataset from existing dataset, where the predictor variables which take place in the model building and those variables are “Company, Target_Audience, Customer_segment, Campaign_Type” and response values are engaged and conversion.
 
•	In the above picture, from “conversion rate” a new column named “conversion” where if the conversion rate is greater than equal to “0.07” then it is “1” and if not, it is “0”.
 
•	In the encoding process, encoding done by factorize encoding has been used to convert the variables in the categorical to numeric variable for model building process. 
 


•	This above picture shows the output of the encoding by factorize () where the values inside the columns have been factored to 0,1,2,3,4 like this (For e.g. there are 5 campaign type then it will be assigned as 0,1,2,3,4)
 
•	Train-Test Split: This approach involves splitting the dataset into training and testing subsets. The model is trained on the training set and evaluated on the separate testing set to assess its performance on unseen data.
•	Before Splitting the data for model building, where in X the categorical variables are assigned and y predictor values.
•	Splitting the Train and Test as “X_train, X_test, y_train and y_test” then assigning the test_size as 30% and training size as 70% and randon_state = 42(it is the optimum value).
 
•	After splitting the X train, test and y train, test then performing shape command to display the size of the rows. Where X train and y train size are (140000 rows and 5 columns) and X test and y test size are (60000 rows and 1 column).
•	Logistic regression: Logistic regression is a statistical model that estimates the probability of an event occurring based on a given dataset of independent variables.

•	Performing the model logistic regression for the X and y and is executed successfully and it displays that current function value is 0.671942 out of 1.00 and displaying the 4 categorical values included in the model as iteration. 
•	Once the regression is performed now test data taken for prediction, after applying the code for prediction the model has been executed successfully. 
 

•	Coefficient (0.0376), Std Err (0.003), z (12.888), P>|z| (0.000) - This suggests a positive relationship between the company, campaign type, channels used, customer segment, target audience and conversion. A one-unit increase in the company variable (whatever it represents) is associated with a 0.0376 increase in the log odds of conversion. The p-value (very close to zero) indicates a statistically significant relationship.
•	The coefficients show that all the predictor variables (Company, Target_Audience, Channel_Used, Customer_Segment, Campaign_Type) have a positive relationship with conversion and are statistically significant. This means that higher values of these variables are associated with an increased likelihood of conversion.
Random Forest: Random forest is a commonly-used machine learning algorithm, trademarked by Leo Breiman and Adele Cutler, that combines the output of multiple decision trees to reach a single result. Its ease of use and flexibility have fuelled its adoption, as it handles both classification and regression problems.
 
•	In the above picture, model for random forest has assigned with the number of estimators is given as 200 (The number of trees assigned in the RF model) and max depth is 5 for the random forest model.
 
•	In the above picture, the random forest model command has been executed and also performed successfully and then to display the estimators, “rf_model.estimators_” command has been executed. 


•	In the above picture, the random forest model estimators of each number have been performed with size of arrays to be predicted in the model, which the estimators are 0,2,3 and size of the array as 10.  
•	Finally, two models, logistic regression and random forest have been executed successfully.
 
CHAPTER – VII
MODEL EVALUATION
       Model evaluation in data analysis is a critical step in assessing the performance, reliability, and effectiveness of machine learning models. It involves using various techniques and metrics to gauge how well a model generalizes to new, unseen data and how accurately it predicts outcomes or classifies observations. Model evaluation is essential for ensuring that the developed models are robust, reliable, and suitable for deployment in real-world scenarios. This comprehensive process helps data scientists and analysts make informed decisions about model selection, optimization, and improvement.
IMPORTANCE OF MODEL EVALUATION:
Model evaluation serves several key purposes in data analysis:
•	Assessment of Model Performance: It provides insights into how well a model performs on unseen data, which is crucial for determining its effectiveness in practical applications.
•	Comparison of Different Models: By evaluating multiple models using standardized metrics, analysts can compare their performance and identify the most suitable one for a specific task or problem.
•	Identification of Model Weaknesses: Through evaluation, analysts can pinpoint areas where a model underperforms or exhibits biases, enabling them to refine and enhance the model's capabilities.
•	Validation of Assumptions: Model evaluation helps validate the underlying assumptions made during model development, ensuring that the model aligns with the characteristics of the data and the problem domain.
•	Decision-Making Support: It provides stakeholders with valuable information for making decisions related to model deployment, investment in further development, or adjustments to business strategies.







METRICS FOR MODEL EVALUATION:
        In machine learning, various metrics are used to evaluate the performance of models. The choice of metric depends on the type of problem being addressed (classification, regression, clustering, etc.) and the specific objectives of the analysis. Here are some commonly used metrics:
Various metrics are used to quantify the performance of machine learning models:
•	Accuracy: Accuracy measures the proportion of correctly classified instances out of the total instances. While it's a straightforward metric, it may not be suitable for imbalanced datasets.
•	Precision and Recall: Precision represents the proportion of true positive predictions among all positive predictions, while recall measures the proportion of true positive predictions among all actual positive instances. These metrics are particularly useful for evaluating binary classification models.
•	F1 Score: The F1 score is the harmonic mean of precision and recall, providing a balanced measure of a model's performance, especially when dealing with imbalanced datasets.
•	ROC-AUC Score: Receiver Operating Characteristic (ROC) curve plots the true positive rate against the false positive rate at various threshold settings. The Area Under the ROC Curve (ROC-AUC) summarizes the curve's performance, with higher values indicating better model discrimination.
•	Mean Squared Error (MSE) and Root Mean Squared Error (RMSE): These metrics are commonly used for evaluating regression models. MSE measures the average squared difference between the predicted and actual values, while RMSE is the square root of MSE, providing a measure of the model's prediction error in the original units of the target variable.
•	R-squared (R2): R-squared quantifies the proportion of variance in the target variable that is explained by the model. It ranges from 0 to 1, with higher values indicating better model fit.









 
•	In the above picture it shows the evaluation of logistic regression model, the accuracy and precision are 0.61 out of 1.00, then F1 score is 0.76 0ut of 1.00 
 
•	In the above picture accuracy, precision score and recall score for random forest model have been calculated and accuracy and precision score for train and test is 0.6074 and 0.6075 out of 1.00 and f1 score in train data is 0.7557 out of 1.00 and f1 score in test data is 0.7558 out of 1.00.  
 
CHAPTER – VIII
CONCLUSION
BIBLIOGRAPHY
https://www.kaggle.com/datasets/manishabhatt22/marketing-campaign-performance-dataset
https://www.clicdata.com/blog/analyze-marketing-campaign-performance/
https://aws.amazon.com/what-is/data-preparation/
https://apisero.com/eda-using-tableau/
https://www.geeksforgeeks.org/model-building-for-data-analytics/
CONCLUSION
•	In the campaign the companies have targeted their audience in 5 as Tech Enthusiasts, Foodies, Fashionistas, Outdoor Adventurers and Health & Wellness.
•	In the campaign the companies have targeted the audience based on their age in 5 segments Women (35-44), People in all age groups, Men (18-24), Women (25-34), and Men (25-34)
•	In the campaign around 1,80,00,000 to 2,30,00,000 people have clicked and viewed the details about the campaign through different channels and companies.
•	The companies have used 6 channels for their campaign they are Email, Google Ads, Website, YouTube, Instagram, and Facebook.
•	In the campaign around 1,80,000 to 2,20,000 people have been engaged in the campaign conducted by the companies.
•	From the campaign around 2,500 to 3,500 people have been converted as customers.
•	From the model evaluation process, for this data both logistic regression and random forest is suitable because model evaluation methods (accuracy, precision and f1 score) are same in both variable.
•	From the findings, click rate of the people was around 1,80,00,000 to 2,30,00,000, engagement rate of the people was around 1,80,000 to 2,20,000 and conversion as customer was around 2,500 to 3,500, by this after all campaigning done by the company only 2,500 to 3,500 people have been converted. It is well conversion rate for the companies, but to acquire more customers the companies should analyse and get more insights from the previous campaigns so the companies can create effective content for their target audience. 

