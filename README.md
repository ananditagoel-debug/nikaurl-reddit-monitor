# README for Reddit Monitor Project

## Project Setup
1. **Clone the repository**: Run `git clone https://github.com/ananditagoel-debug/nikaurl-reddit-monitor.git`
2. **Navigate to the project directory**: `cd nikaurl-reddit-monitor`

## Getting Reddit API Credentials
1. **Create a Reddit account** if you don't have one.
2. **Go to Reddit Apps**: [Reddit App Preferences](https://www.reddit.com/prefs/apps)
3. **Create a new application**:
   - Choose 'script' as the application type.
   - Fill in the required fields.
   - Note down your `client_id`, `client_secret`, and `user_agent`.

## Environment Setup
1. **Install dependencies**: Use `pip install -r requirements.txt` to install the necessary packages.
2. **Set up your environment variables**: Create a `.env` file in your project directory and include your API credentials as follows:
   ```
   CLIENT_ID=your_client_id
   CLIENT_SECRET=your_client_secret
   USER_AGENT=your_user_agent
   ```
3. **Run the application**: Use `python main.py` to start the application.

## How the Workflow Works
1. The application connects to the Reddit API using the credentials supplied.
2. It fetches the relevant data based on specified criteria.
3. 
4. The application processes the fetched data and performs actions predefined in the codebase.

Make sure to check the documentation for any additional features or configurations!