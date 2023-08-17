# SMS-Spam-Detection

Advancement in technology has made end-users to access their emails, surf the World Wide Web, make video and voice calls, use text chatting, make a medical appointment, gaming and more through their smartphones. The purposes of SMS spam are advertisement and marketing of various products, sending political issues, spreading inappropriate adult content and Internet offers and phishing attack among others, hence spam SMS flooding has become a serious problem all over the world. SMS spamming gained popularity over other spamming approaches like email and Twitter, due to the increasing popularity of SMS communication. Mobile devices now contain personal and confidential information such as credit card numbers, contact lists, emails, medical records and other sensitive documents. The issue of SMS spam can be attributed to limited resources and processing power and lack of knowledge and consciousness to end-users regarding security threats. The aforementioned reasons make mobiles very eye-catching to cyber-attacks. Hackers can utilize the compromised mobiles to make calls to premium numbers without the end-users’ permission, stealing contact data, or participating in botnet activities.
The exchange of SMS among different mobile phones is very suitable and regularly used for communication on a day to day basis. Then, the number of spam SMS messages is growing. In 2012, there were 350,000 variants of SMS spam globally. SMS has been considered a serious security threat since the early 2000s. For instance, hackers can send phishing attacks to collect confidential information or launch other types of attacks. The risk of SMS spam could lead to operational or financial loss. It is getting easier to attack end-users through SMS than emails, since the mail service is more secure, and more effective email spam filter has been developed and installed by mail service providers and users.

Dataset:
The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged according being ham (legitimate) or spam. The files contain one message per line. Each line is composed by two columns: v1 contains the label (ham or spam) and v2 contains the raw text.  It has 1,002 SMS ham messages and 322 spam messages and it is public available at Kaggle.

•	Importing and reading the dataset

•	Data Cleaning: This step involves removing of null values and unwanted columns in our dataset. Giving proper naming to attributes. Removing of duplicate and missing values are performed in this step.

•	Performing EDA: In this step we are counting number of ham and spam text in our dataset. Counting the number of characters, words and sentences in each paragraph of spam dataset.

•	Data Preprocessing: In this step we are performing NLP operations on our dataset - 1. Lower Case 
                         2. Tokenization
                         3. Removing special Character 
                         4. Removing stop words and punctuation 
                         5. Stemming

•	Model Building: Applying machine learning algorithms and building the model.
