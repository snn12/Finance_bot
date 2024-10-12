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
1. Go to the [Reddit App Preferences](https://ssl.reddit.com/prefs/apps) page
2. Click "Create App" or "Create Another App"
3. Fill in the required information:
   - Name: The name of your application
   - Select App type: "script"
   - Redirect URI: http://localhost:8080
4. Click the "Create app" button
5. "client_id" (under the "name of the application " (top left) and "client_secret"

  
update the ``config.py`` file on your PC:
```
REDDIT_CLIENT_ID = 'your_client_id'
REDDIT_CLIENT_SECRET = 'your_client_secret'
REDDIT_USER_AGENT = 'your_user_agent_name'
```

### Configuring the Twitter API
1. Register on the [ RapidAPI ](https://rapidapi.com/) website
2. Subscribe for  [Twitter API v2](https://rapidapi.com/restocked-gAGxip8a_/api/twitter-api47)
3. Get your API key. You can make 3000 requests per month for free.
You can also use the official API : https://developer.x.com/en/products/x-api


update the ``config.py`` file on your PC:
```
RAPIDAPI_KEY = 'your_rapidapi_key'
RAPIDAPI_HOST = 'twitter-api47.p.rapidapi.com'
```
