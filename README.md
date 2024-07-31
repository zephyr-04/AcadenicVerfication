# AcademicVerfication
This project implements a decentralized application (DApp) for verifying academic credentials using the Ethereum blockchain. The smart contract is written in Solidity and deployed using the Remix IDE. The system allows educational institutions to issue, revoke, and update academic credentials for students.

## Features
- Role-Based Access Control: Utilizes OpenZeppelin's AccessControl to manage roles for institutions and students.
- Credential Management: Institutions can issue, update, and revoke academic credentials.
- Verification: Third parties can verify the authenticity and details of academic credentials.
- Event Logging: Key actions such as credential issuance, revocation, and updates are logged via events.
