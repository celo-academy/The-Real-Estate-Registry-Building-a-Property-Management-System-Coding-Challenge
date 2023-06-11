## Introduction

Solidity is the core language for creating smart contracts on blockchain platforms like Celo. These contracts can be used to construct decentralized applications with real-world applications, such as property management systems. In this challenge, you will build a contract for managing real estate transactions.

## Problem Statement

Create a smart contract that simulates a basic property management system with the following requirements:

1. The contract should allow property owners to register their properties, specifying details like property ID, size, and location.
2. The contract should allow property owners to transfer ownership of their properties to other addresses.
3. The contract should allow anyone to verify the current owner of a property.
4. The contract should prevent property registration if the property ID already exists.
5. The contract should prevent property transfer if the sender is not the current owner.

## Hints

- Use a `struct` to define a property with attributes such as property ID, size, location, and owner address.
- Use a `mapping` to link property IDs with their respective property data.
- Use `msg.sender` to assign property ownership during registration and transfers.
- Use `require()` function to enforce rules such as property ownership during transfers and unique IDs during registration.

## Evaluation Criteria

- **Correctness**: The contract should compile without errors and meet all the requirements.
- **Readability**: The contract should be well-documented, with comments explaining the code.
- **Testability**: You should also provide examples of how to test each function of the contract.

Keep in mind, this challenge primarily focuses on property management concepts and doesn't cover key aspects like security, gas optimization, and contract upgradability, which are critical in a real-world scenario on the Celo platform.

For a comprehensive understanding of Celo smart contracts and Solidity, please refer to the Celo and Solidity tutorials.

## Submission

Please reply with a link to your PR on GitHub, including your property management system contract. Also, include any notes or comments you think are necessary to understand your design and choices. Lastly, provide a brief explanation about how each function of the contract should be tested.
