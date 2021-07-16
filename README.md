# Play-Store
This analysis will provide you top apps according to different categories.

**Project : Play-Store Analysis.

**Work Done :

• Checked distibution of data by using 'histogram' and remove outliers.
• Used 'fillna' to fill all the missing values.
• For categorical columns used 'mode' to fill all the missing values and for numerical columns used 'median' to fill all the missing values .
• Used 'derop_duplicates' (set subset = 'App' for selecting App column) on column App and removed duplicate rows which have same application name.
• Some columns has '$','+' characters present inside rows therefore used string replace in lambda function and applied on that particular columns to replace '$', '+'             characters. 
• Some numerical columns shows as object datatype therefore used 'astype' and converted object datatype into float datatype . 
• Used 'value counts' and 'nlargest' , plotted 'pie' chart to get information about maximum category apps.
• Used 'groupby' on category column to get maximum rating, reviews and installs for plotting graph of that.
• Used 'logical operators' for conditions and 'sort values' to get the top free apps, top paid apps and best game app on play store.

**Choose this project to find out following information **:

• Find the top apps on play store. 
• Find the best game app on play store. 
• From a developer point of view which types of category apps should create for better profit. 

**Conclusion :

 From the above analysis we can summaries as follow :
    
1. Play store contains maximum "Family" category apps followed by "Game" and "Tools" category apps.
2. ART_AND_DESIGN , EVENTS , HEALTH_AND_FITNESS, MEDICAL, WEATHER app posses maximum installs.
3. EVENTS Category possessd higher rating average followed by EDUCATION, ART_AND_DESIGN, BOOKS_AND_REFERENCE,
   PERSONALIZATION category.
3. Play store possessed maximum apps of "Everyone" content rating where as "Teen" content rating stand after "Everyone" content 
   rating.
5. There are total 8903 free apps and 756 paid apps thus it shows that number of free apps are far more compare to paid apps.
6. The top free apps are as follows:
       Category :                    App 
    
    1.COMMUNICATION         1.WhatsApp Messenger  
                            2.Google Chrome: Fast & Secure   
                            3.Game  
        
    2.ENTERTAINMENT         1.Google Play Games
    
    3.GAME                  1.Subway Surfers
    
    4.SOCIAL                1.Instagram
    
    5.PHOTOGRAPHY           1.Google Photos
    
    6.TRAVEL_AND_LOCAL      1.Maps - Navigate & Explore
    
    7.TOOLS                 1.Google
    
    8.PRODUCTIVITY          1.Google Drive
    
    9.VIDEO_PLAYERS         1.YouTube
    
7.The top paid apps are as follows:
     
     Category                     App 
    1.FAMILY                1.Minecraft
    2.GAME                  1.Hitman Sniper 
    
 # Result :
1. Top free apps possessed more Communication category apps.
2. Minecraft and Hitman Sniper are the top paid apps.
3. Subway Surfers is the best game app on play store.
4. If you are a android developer so you can see this top apps according to category and create similar category apps for profit.
