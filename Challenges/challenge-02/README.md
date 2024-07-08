<p align="center">
  <img src="./assets/TN-Challenge-2.png" alt="Challenge-2"/>
</p>


# Challenge 02

## Problem Statement
Successfully gridlock this contract with a DoS attack.


**Task**:

- Create a solidity contract that will attack this contract and gridlock it.
- Using Remix: 
  - 1. Use a dedicated wallet and deploy the `Target` contract.
  - 2. Deposit 50 ETH using the deposit method.
  - 3. Verify the contract balance is 50 ETH.
  - 4. Create and deploy your `Attacker` contract.
  - 5. Perform your attack.
  - 6. Verify the contract is gridlocked by trying to withdrawAll from the `Target` contract.
  - 7. You are successful if the contract is gridlocked and you are unable to withdrawAll. 
- Provide your solution and comments in the Discussion for this challenge.

**Constraints**:

- Use Solidity 0.8.x or higher.

**Author**: [passandscore](https://github.com/passandscore)

---
<br/>

<a href="https://remix.ethereum.org/#url=https://github.com/passandscore/solidity-challenges/blob/main/Challenges/challenge-02/Challenge.sol" style="
    display: inline-block;
    padding: 2px 10px;
    font-size: 16px;
    color: black;
    background-color: #D2D2D2;
    text-align: center;
    text-decoration: none;
    border-radius: 5px;
    display: inline-flex;
    align-items: center;">
<svg xmlns="http://www.w3.org/2000/svg" version="1.1" viewBox="0 0 1680 1600" width="40" height="40">
<path transform="translate(872,242)" d="m0 0 29 3 28 5 30 7 26 8 2 2v49l-1 48 7-4 13-13 8-7 6-6h2v-2l8-7 12-11 13-12 3-3 7 1 19 11 27 18 11 8 14 11 14 12 6 5-1 5-7 15-19 41-13 29-1 3 14-5 62-21 18-6 4 1 10 13 18 27 15 26 9 17 6 13-1 4-8 8-11 9-13 12-11 9-13 12-11 9-9 8 3 1 97 9 5 2 4 14 7 43 3 35v21l-30 10-71 22-1 2 5 2 22 12 64 36 3 3-1 9-7 30-7 25-9 25-12 29-8 16-5 9-9 4-411 137-7 1-35-12-43-14-288-96-44-15-8-3-6-9-13-27-11-27-9-27-8-30-4-19v-5l5-4 13-7 23-13 52-29-4-3-54-17-42-13-1-1v-21l3-36 5-32 5-23 2-2 16-2 87-8-15-15-11-9-12-11-8-7-10-9-11-9-10-9 2-5 11-23 10-19 13-21 8-12 14-19 4-1 40 13 34 12 18 6 2 1-7-17-13-29-7-15-10-21-4-10 7-8 10-8 16-13 17-12 18-12 25-15 5 1 15 14 39 36 12 11 6 4-1-52v-46l5-3 35-10 34-7 29-4h13l12 27 18 42 7 17v2l3-1 18-41 16-38 4-8z" fill="#020101"/>
<path transform="translate(796,64)" d="m0 0h72l37 3 31 4 33 6 44 11 26 8 33 12 28 12 20 9 19 10 24 13 24 15 22 15 19 14 18 14 14 12 10 9 8 7 17 16 13 13 7 8 12 13 9 11 11 13 12 16 13 18 12 18 13 21 13 23 14 27 14 31 12 31 11 33 8 28 1 1 32 1 27 3 23 5 17 5 18 8 11 6 14 10 15 15 9 14 7 15 4 17 1 9v62l-2 41-4 39-5 32-7 32-9 29-10 25-8 16-9 16-13 18-13 15-11 11-13 10-14 8-19 8-23 6-24 4-16 2-16 1h-33l-29-2-30-3-29-4-12-3 1-5 13-21 10-17 8-16 12-25 13-32 12-36 8-30 6-29 5-34 3-34v-60l-3-36-6-39-8-36-8-28-10-29-12-29-16-33-13-24-12-19-12-18-14-19-11-14-11-13-7-8-14-15-22-22-8-7-10-9-14-11-13-10-18-13-17-11-25-15-28-15-28-13-28-11-34-11-26-7-40-8-31-4-25-2h-71l-33 3-32 5-36 8-28 8-32 11-29 12-33 16-23 13-26 16-14 10-19 14-17 14-8 7-20 18-21 21-7 8-11 12-11 14-14 18-14 20-12 19-12 21-12 23-12 25-13 33-11 34-8 31-6 29-5 37-2 26v68l3 32 6 38 9 39 11 35 9 25 10 23 12 25 12 23 18 30 1 4-7 2-44 6-32 3-18 1h-32l-26-2-27-4-17-4-18-6-16-8-11-7-14-12-9-9-7-8-13-17-11-18-11-21-10-26-8-27-6-25-6-37-4-38-2-33v-77l3-15 4-12 7-14 8-11 16-16 15-10 16-8 19-7 25-6 20-3 13-1 32-1 3-9 10-33 11-32 13-31 17-35 10-19 16-27 7-11 13-19 13-18 20-25 13-15 12-13 9-10 19-19 8-7 14-13 11-9 17-14 19-14 20-14 19-12 22-13 24-13 29-14 31-13 34-12 26-8 36-9 32-6 28-4 29-3z" fill="#020101"/>
<path transform="translate(404,1042)" d="m0 0 9 1 249 83 40 13 41 14 43 14 41 14 7 1 47-16 342-114 31-10h6l-1 4-425 425-5-1-424-424z" fill="#020101"/>
</svg> 
<span style="margin-left: 10px;">Load in Remix IDE</span>
</a>
