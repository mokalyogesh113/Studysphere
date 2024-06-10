# MERN Project

This is a MERN (MongoDB, Express.js, React.js, Node.js) project with separate folders for the client-side and server-side code.

## Project Structure

- `CLIENT/`: Contains the React.js front-end code.
- `SERVER/`: Contains the Node.js back-end code.

## Server Configuration

### API Keys

In order to run the server, you'll need to provide your own API keys for certain services. In the `SERVER/server.js` file, there are two variables named `accountSid` and `authToken` which are used for authentication with a specific service.

To set up these API keys:

1. **Obtain API Keys**: Obtain your API keys from the service provider's website.
2. **Set Environment Variables**: Set the following environment variables on your server or in your development environment:
```
const accountSid=YOUR_ACCOUNT_SID
const authToken=YOUR_AUTH_TOKEN
```

Replace `YOUR_ACCOUNT_SID` and `YOUR_AUTH_TOKEN` with your actual API keys.

## Client Configuration

### API Keys
In order to run the client, you'll need to provide your own API keys for serverAPI. In the `CLIENT/src/utils/api.js` file, there is a variable named `serverApi` which is used for backend API calls.


...

## Running the Project

To run this project locally:

1. **Start the Server**:
- Navigate to the `SERVER/` directory.
- Run `npm install` to install dependencies.
- Run `npm start` to start the server.

2. **Start the Client**:
- Navigate to the `CLIENT/` directory.
- Run `npm install` to install dependencies.
- Run `npm start` to start the client.

3. **Open in Browser**:
- Once both the server and client are running, open your web browser and navigate to `http://localhost:3000/`.

<!-- ## Deployment -->


