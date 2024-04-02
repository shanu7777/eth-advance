# Eth Advance
This contract implements a vesting mechanism for distributing tokens to stakeholders over a specified period of time. It allows organizations to create stakeholders, set vesting periods, and whitelist addresses for t# Requirements:
1. MetaMask extension installed in your web browser.

#Getting Started:

1. Clone the Repository:
   Download the entire repository from GitHub to access all the project contents.

2. Install Dependencies:
   In the project directory, open your terminal or command prompt and run the following command to install the required dependencies using npm:

   ```
   npm install
   ```

3. Start Local Hardhat Node:
   After installing the dependencies, run the following command to start the local Hardhat node:

   ```
   npx hardhat compile
   ```

4. Deploy the Contract:
   Open a second terminal and deploy the contract on the local Hardhat node using the following command:

   ```
   npx hardhat run scripts/deploy.js --network mumbai
   ``

5. Start the Frontend:
   In the second terminal, run the following command to start the application frontend in development mode:

   ```
   npm run dev
   ```

6. View the Application:
   Open  http://localhost:5173/ in your web browser to view the application. You should see the values of the functions displayed on the frontend.

Additional Commands:

- Get Help: To get help or view available Hardhat commands, run:

  ```
  npx hardhat help
  ```

- Test the Contract: To run tests for the smart contract, use the following command:

  ```
  npx hardhat test
  ```

# License
This project is licensed under the MIT License.
- - -
