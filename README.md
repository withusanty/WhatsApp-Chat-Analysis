# WhatsApp Chat Analysis
## About this project:
- The main goal of this project is to analys the whatsapp chat and represents through charts and visuals.
- Project is live now and deployed on heroku. visit at https://whatsapp-santosh.herokuapp.com/
- This projects can be used for indivisual as well as group chats.
​
## Idea:
1. Created a function that convert WhatsApp chat text file into dataframe with columns name(['date', 'year', 'month', 'day', 'hour', 'minute', 'month_name','day_name', 'user', 'message', 'message_chars'])
​
2. Which Data you will get in this analysis
1. Sum
    - Chat starting date, first entry in chat
    - Chat Ending Date, last entry in chat
    - Total Members in chat, only those who had sent atleat one message
    - Total Messsages, including messages, missed calls, media, links
    - Total Words of Messages, 
    - Total Media File Shared
    - Total Links Shared
    - Total Missed Calls
2. Bar chart of no messages sent by members
3. Bar chart of no messages sent by members with mean line
4. Pie chart with no if messages sent in %
5. Pie chat of Who started and ended chat most of the time
6. WordMap of most 75 words used in chat with stopwords and without stopwords
7. Box Plot of who sent the longest messages
8. Pie chart of most used emoji
9. Sunburt chart of members and thier weekly messages(and yearly,monthly,weekly)
10. Line chart of Daily chat activity(same monthly, yearly) for all and indivisuals
11. Heatmap represents which has occured more on given to features
12. Table of 5 longest message in entire chat
13. Table of 5 Longest message of highest chat happened on a single day
14. Table of all shared links in chat
    
## Charts used to represents data:
    - Bar, Line, Box, WordMap, Sunburst Heatmap
    
## Librabry used
   - **streamlit** : for web application
   - **matplotlib**: for charts 
   - **plotly** : intrective charts
   - **pandas**: for creation of dataframe
   - **PIL**: opening image file 
   - **re** : regular expression
   - **urlextract**: for extracting URL from chat
   - **collections**: for counting each words
   - **wordcloud**: creating wordmap
   - **emoji**: extracting emoji from chat
   - **warnings**: ignore warnings
​
# Code written in pycharm in three files
- **app.py** : main file
- **dataset.py**: for generatig dataset
- **functions.py**: user defined functions as per required
​
#### Project Files link: https://github.com/withusanty/WhatsApp-Chat-Analysis
​
# How to use:
1. To use this webapp first you whatapp chat txt file.
    - You can try your whatsapp of any individuals or groups chat this is 100% SAFE and SECURE, I don't have access to this webapp. So, feel free to use.
    - To export your chat: follow the steps given below:
        - Open your whatsapp in mobile only
        - Open any chat
        - click on three vertical dots (upper right corner)
        - click on More
        - click on Export Chat, proceed with Without Media
        - Now save this file anywhere you want.
        
2. Now, vist at https://whatsapp-santosh.herokuapp.com/
3. Page will look like below
![what.png](attachment:63d3f9e1-b565-4b79-beeb-752681d6c585.png)
4. To see details how it works click on plus icon '+', click again '-' to close
![image.png](attachment:d12869db-e346-4f48-8f12-9a9b3a774fad.png)

5. Browse your file or drang and drop in the file box.
6. Once your file has been uploaded all members name will be visible in dropdown menu,default selecte All, if you want to analys for indivisual member then select that member and click on 'Show Analysis'.
![what2.png](attachment:91e594f6-c364-4aeb-8377-256136a6c693.png)

# Few Results Snapshots:
![what3.png](attachment:458ce0c8-28dc-445b-bb6b-3c6d72c638e2.png)
![what4.png](attachment:69ec0681-d019-4651-8240-e5407cd4dc7c.png)
![what5.png](attachment:5ad289e7-fcd9-4684-9c6a-d6c7fa95f2ae.png)
![what6.png](attachment:df4fabee-efcc-468b-95b4-aa8f9ef3cf5b.png)
![what7.png](attachment:5490420f-c581-45de-8c87-3bfc0fa16afd.png)
![what8.png](attachment:d1bafe8c-f122-4607-8093-2af42213bdde.png)
![what9.png](attachment:c79f0823-019e-4119-b6ed-b738ecc8dfd5.png)
![what10.png](attachment:5351a0b1-0ae8-4592-90e9-91972604b60f.png)
