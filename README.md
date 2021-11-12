# Call Performance Demo Application (Node.JS)

This is a straight forward Node.JS based console application that demonstrates how to use RingCentral's Analytics (Call Performance APIs). The resulting JSON is rendered on the standard console. 

More information about that can be found in the [developer guide.](https://developers.ringcentral.com/guide/analytics)

## PreRequisite:

1. Node.JS
2. Have a RingCentral Application with 'Analytics Permission' in your Developer Console. If not, you can easily create one by signing up for a [free developer account.] (https://developers.ringcentral.com/login.html#/)
3. Get the RingCentral Application ID & Secret Key from Developer Console. This application uses "Production" credentials but you can also use your "Sandbox" credentials.
4. You need to create a .env file to load your credentials.

## Steps to run the program

1. Clone/Download this GitHub Repository
2. Open the project in any IDE such as Visual Studio Code
3. Edit the .env file with your Application Credentials
4. After editing the .env file run the following commands

```bash
cd <repo>
npm install
node index.js
```
5. Open Console to see the JSON Response shown for both 'Aggregrate' and 'Timeline' data as returned by the two Call Performance APIs.

