# slack-github-issue
Code for Slack bot to auto comment the issue information for a specific repository when a user types the issue number.

Makes use of [node-slack-client](https://github.com/slackhq/node-slack-client).

## How to run
1. Clone repo into your local machine (`https://github.com/augbog/slack-github-issue.git`)
2. Navigate to folder (`cd slack-github-issue`)
3. Run `npm install`
4. Go to `index.js` and update `BOT_TOKEN`, `REPO_OWNER`, and `REPO_NAME`
5. Run `node index.js`