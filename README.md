## Running the demo

To run the demo follow these steps:

1. Clone the project with the code below.

   ```sh


   git clone https://github.com/Yash-Kalekar/-Answer-To-Earn-DApp-with-NextJs-TypeScript-Tailwind-CSS-and-Solidity.git
   cd answerToEarn # Navigate to the new folder.
   ```

2. Create a `.env` file to include the following details.
   ```sh
    NEXT_APP_RPC_URL=http://127.0.0.1:8545/
   ```
3. Start the HardHat Server in first terminal:
   ```
    npx hardhat node
   ```
3. On second terminal, run the app using:
   ```
    yarn install
    yarn hardhat run scripts/deploy.js
   ```

4. On third terminal, run the app using `yarn dev` to launch on the browser.
   <br/>
