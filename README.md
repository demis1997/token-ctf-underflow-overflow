# token-ctf-underflow-overflow
Example ctf with underflow and over flow, not using safemath

The point is to receive and insane amount of tokens by transfering them. Ofcourse buying these is not an option so there is another way.
The contract is not using safemath.sol which means that overflows and underflows can happen here. Simply transfer more than 20 or less than 0 tokens.
Transferring less than 0 in this case did not work and transfering 21 didnt either.
In the end i transferred 21 tokens to another smart contract instead of a wallet address and it worked.
<img width="1536" alt="token" src="https://user-images.githubusercontent.com/63403890/185680285-10ce3b23-5d66-48dd-a908-725cc2d2dfba.png">
