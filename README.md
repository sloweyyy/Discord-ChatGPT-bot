# Discord ChatGPT Bot

Welcome to the Discord ChatGPT Bot! We've upgraded to using the official ChatGPT API for more reliable and consistent responses. If you still prefer the unofficial API version, you can find it on the "non_official_api" branch.

Thank you for using our bot and contributing to the project!

## Features

Our Discord ChatGPT Bot comes with a range of powerful features:

Ask Anything: You can ask any question using the `/ask 'question'` command.
Generate Images: Create images by using the `/image 'prompt'` command.
Edit Profile Pictures: Modify other members' profile pictures with `/remix @mentionuser prompt`.
Generate Videos: Generate videos with `/video prompt`.

## Getting Started

To get started with the Discord ChatGPT Bot, follow these steps:

1. Rename the .env.example file to .env.
2. Fill in the .env file with the required configurations.
   3.Start the bot using one of the following methods:

### Using Node.js

```
npm install
npm start
```

### Using Docker

```
docker build -t discordchatgpt .
docker run -p 8080:8080 -v discordchatgptconfig:/discordChatGpt/configFile discordchatgpt
```

## Dashboard

We've introduced a convenient dashboard for configuring the bot, eliminating the need to restart it to modify settings. The bot runs on port 8080. We also have plans to integrate usage statistics into the dashboard for your convenience.

Enjoy using the Discord ChatGPT Bot, and feel free to reach out if you have any questions or feedback!
