# WhisprChain
A tamper-proof, anonymous platform for whistleblowers to submit evidence using blockchain and IPFS — protecting truth-tellers worldwide.

---

## Description

This project is a **private blockchain-based real-time reporting platform** designed to help individuals submit reports relating to specific events with a high level of integrity. The system is designed to ensure that no data can be tampered with or falsified, thus creating a permanent, auditable record. The platform is tailored to allow users to submit, explore, and search reports while maintaining privacy and anonymity. 

The key features include:
- **Free Speech Platform**: Users can freely submit reports with minimal censorship.
- **Anonymous Submissions**: All submissions are kept anonymous for privacy.
- **Real-Time Blockchain Explorer**: A blockchain-based ledger that records all submissions, making it tamper-proof and auditable.
- **Search Functionality**: A comprehensive search feature to allow users and law enforcement to search reports based on various parameters such as events, keywords, and more.

---

## Features

### 1. **User Submissions**
- **Private Reporting**: Users can submit event reports that are anonymously stored on the blockchain.
- **Unrestricted Content**: Users have freedom of speech with no censorship (excluding illegal content).
- **Timestamp & Integrity**: Each report is timestamped and recorded on the blockchain, ensuring authenticity.

### 2. **Search Functionality**
- Users can search through the blockchain for reports related to any specific event or keywords.
- Provides an easy way for law enforcement and authorities to investigate reports related to specific incidents.

### 3. **Proof Viewer for Authorities**
- **Verification Mechanism**: Authorities (like law enforcement) can verify the authenticity of reports without exposing the identity of the reporter.
- **Decentralized Control**: Only authorized entities can access the full details, while maintaining the anonymity of users.

### 4. **Blockchain Implementation**
- **Immutable Record**: Blockchain technology ensures that once a report is recorded, it cannot be altered or deleted.
- **Real-Time Blockchain Explorer**: View reports in real-time via a blockchain explorer interface.
- **Event Traceability**: Every report is linked to specific events, which can be traced through a decentralized ledger.

### 5. **Custom License**
- **Private Access Only**: This software is only available to individuals or organizations with explicit permission from the project owner.
- **Restricted Usage**: Unauthorized usage, distribution, or modification is prohibited.
- **No Commercial Use**: The software is non-commercial unless explicitly authorized.

---

## Tech Stack

- **Frontend**:  
  - HTML5, CSS3, JavaScript (React or Vue.js for frontend framework)
  - Web3.js or Ethers.js for interacting with the blockchain
  
- **Backend**:  
  - Node.js (Express.js for REST API)
  - MongoDB or PostgreSQL for storing metadata (non-sensitive data)
  - Ethereum Blockchain (for blockchain implementation)
  - IPFS (InterPlanetary File System) for storing report data securely
  
- **Blockchain**:  
  - Ethereum (for public, decentralized storage of reports)
  - Smart Contracts (to manage submissions, metadata, and events)
  
- **Other Technologies**:  
  - Docker (for containerization)
  - AWS or DigitalOcean (for deployment)
  - CI/CD tools (GitHub Actions, Jenkins)
  
---

## Project Workflow

### 1. **User Interaction**
- **Step 1**: Users visit the platform’s interface.
- **Step 2**: They submit an event report (free speech, anonymous).
- **Step 3**: The report is sent to the backend for processing and timestamping.
- **Step 4**: The report data is stored in IPFS (for decentralized storage).
- **Step 5**: The report metadata is recorded on the Ethereum blockchain with a timestamp for verification.

### 2. **Search Functionality**
- **Step 1**: Users can search for reports related to specific events using keywords or event IDs.
- **Step 2**: Search results are displayed from the blockchain explorer interface.
  
### 3. **Proof Viewer for Authorities**
- **Step 1**: Authorities access the proof viewer.
- **Step 2**: They enter the event ID or report hash.
- **Step 3**: The report’s authenticity and details are verified on the blockchain, while maintaining the anonymity of the reporter.

### 4. **Blockchain Interaction**
- **Step 1**: Every submitted report creates a new block on the blockchain.
- **Step 2**: The block includes metadata such as the event, timestamp, and hash of the report (but not the sensitive content).
- **Step 3**: This immutable record ensures no future tampering of reports.
  
---

## Deployment Process

### Step-by-Step Workflow for Deployment

1. **Set up Development Environment**:
   - Install necessary software (Node.js, Ethereum development tools).
   - Clone the repository and install dependencies using `npm install`.
  
2. **Set up Blockchain**:
   - Deploy Ethereum smart contracts on a testnet or the mainnet.
   - Use Web3.js or Ethers.js to interact with the blockchain from the backend.

3. **Backend Setup**:
   - Implement the API to handle report submissions, searches, and proof verifications.
   - Use IPFS to store the data (e.g., report files or media) and return an IPFS hash to be stored on the blockchain.

4. **Frontend Setup**:
   - Design a responsive UI using React or Vue.js.
   - Integrate the frontend with the backend API for submitting and searching reports.

5. **Security**:
   - Implement encryption for sensitive metadata.
   - Secure communication with HTTPS and encrypted API calls.

6. **Testing**:
   - Write unit tests for API routes and smart contracts.
   - Test blockchain interactions on a testnet to avoid unnecessary costs.

7. **Deployment**:
   - Deploy the application on a cloud service like AWS or DigitalOcean.
   - Use Docker for containerization to ensure scalability.
   - Set up continuous deployment pipelines using GitHub Actions or Jenkins.

---

## Project Flow After Deployment

1. **User Access**: Users can visit the website and submit their reports.
2. **Report Storage**: Reports are stored securely on IPFS, and their metadata is recorded on the Ethereum blockchain.
3. **Blockchain Record**: Every report is recorded as a block, ensuring that no data can be altered or deleted.
4. **Search Functionality**: Users or law enforcement can search the blockchain for reports related to specific events.
5. **Verification by Authorities**: Authorities can verify report authenticity through a secure viewer without revealing the identity of the reporter.
6. **Real-Time Updates**: The blockchain explorer updates in real-time as new reports are submitted and processed.

---

## License

This project is licensed under the **Custom Proprietary License**, which means it is private and only accessible to individuals or organizations that have received permission from the author. Unauthorized use, modification, or distribution is prohibited.

---

## Contributing

We welcome contributions from trusted individuals. Please contact the project owner to request access if you are interested in contributing. All contributions must follow the project’s guidelines, including maintaining the privacy of the users.

---

## Contact

For any inquiries or requests, please contact project owner .

---

## Acknowledgments

- Special thanks to the Ethereum community for the development tools.
- Thanks to [mention any contributors or resources].
