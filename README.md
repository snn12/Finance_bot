# Finance_bot
Here we will get the information from Twitter ( X ) and Reddit social networks, clean the received information and then analyzes it using GPT-4o, and generates detailed report. Have a nice day :)

## Features
* Collecting stock-related comments from Reddit and Twitter (X).
* Data filtering and cleaning and validation
* Market analysis using GPT-4o
* Creating reports for each ticker and saving the Results in Markdown format

## Installation

1. Clone the repository :
```
git clone https://github.com/snn12/Finance_bot.git
cd Finance_bot
```
2. Install dependencies :
```
pip install -r requirements.txt
```
## Configuration

### Configuring the Reddit API
1. Go to the  page
2. Click "Create App" or "Create Another App"
3. Fill in the required information:
   - Name: The name of your application
   - Select App type: "script".
   - Description: A short description of your bot
   - About URL: Can be left blank
   - Redirect URI: http://localhost:8080

Click the "Create app" button
Note "client_id" (under the name of the application) and "client_secret".


 ['Reddit App Preferences'](#https://ssl.reddit.com/prefs/apps) 
