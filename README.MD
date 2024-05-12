# Steps to set up the extension
This is the Chrome Extension For Tracking Every page's visit time and the time duration. The Procedure For Running these files:

1. Go to Setting
2. Find Out Extension Page
3. Click on that
4. Developer Mode On
5. Click On Load Unpacked
6. Upload Folder which is having # manifest.json file
7. Click On the Extension and Pin this Extension

# Checklist

## Features list

1. Track Activity  
    ==>Time Spent on each Website (Active Tab)  
2. Productive Browsing   
    ==>Users should be able to add and delete websites to restricted lists.  
        -->If they visit restricted sites, they will see the warning and cannot proceed to that website.  
        -->For example: A user has added netflix.com in the restricted list, they will not be able to open Netflix.  
    ==>Users can set a time limit on websites.  
        -->If they exceed the time restriction, the tab will be automatically closed.  
        -->For example: An user has set a time restriction of 30 minutes, so after 30 minutes ends, the user will not be able to access that website.  
3. A Personalized Dashboard: where each user can see their website usage.  
    ==>Users should be able to see the time they spent on each website, data should be presented in the form of a graph or other similar metrics.  
    ==>When clicked on a specific website from the list, Users should be able to see detailed analytics for that website, such as time spent on each page, idle time, active time, etc.  

## Additional Features

1. Data Filter - Generate Reports daily, weekly, monthly and yearly.  
2. False Negative - The application should be able to determine if the screen is idle or not, i.e. the user is showing some activity or not in the tab and store the data accordingly.


# Values

This is a chrome extension that monitors and summarizes the user's web activity. The purpose of this extension is to self analyze one's web usage and increase productivity by greylisting/blacklisting the websites that user finds unproductive.

## Today's Usage

Displays the list of websites visited in the last 24 hours along with the time spent on each of them. The time of the currect focused webpage time is also displayed as a badge on the icon of the extension.
A pie chart showing the time statistics is displayed above the list.

## All Time Usage page

Similar to "Today's Usage", but displays data collected accross all time of universe.

## Options

- Blacklisting of websites: The user may add a website to the blacklist with a certain time limit (defaults to 0). When the time limit of the website goes below 1 minute, the extension icon badge turns red and displays a countdown of 60 secs. After this time is exhausted the website gets blocked. If said website is removed from blacklist the blocked page redirects back to the website.  

- Daily reset: By default the today's usage data is reset at 4:20AM, however the user can manually set this time.  

- Reset: The user can reset the total collected data for today, or all time.  
