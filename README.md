# ReachInEmailAuto
Server
The assignment is to build a tool that will parse and check the emails in a Google and Outlook email ID, and respond to the e-mails based on the context using AI. Use BullMQ as the tasks scheduler This is a server-based application built with Node.js and Express. It uses various packages such as openai for AI functionalities, googleapis for Google APIs, and axios for HTTP requests and bullMQ to process queues.

Technologies used:
Node.js
Express.js
OpenAI
Google APIs
Microsoft Graph API
npm packages used:
dotenv
Axios
bullMQ
google-auth-library
ioredis
@microsoft/microsoft-graph-client
@azure/msal-node

Installation setup
Clone the repository to your local machine
git clone https://github.com/shraddha-gawde/reachInbox-assignment.git
Navigate to the root directory of the project directory :
cd server
Run npm install to install all the dependencies
Create a .env file in the root directory with the same IDs as specified in the documentation.
Running the server
To start the server, run the following command in your terminal
npm start
This will start the server at localhost:5000 (or whatever port you have specified). or we can use backend deployed link also.

To start the worker.js file, run the following command in your terminal
npm run server
