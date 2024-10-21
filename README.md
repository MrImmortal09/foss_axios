# Next.js 14 and Hardhat Integration

This repository contains a basic Next.js 14 application and a Hardhat configuration for deploying smart contracts.

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm or yarn
- Hardhat

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/YourUsername/YourRepo.git
   cd YourRepo
   ```

2. Install the dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

### Running the Next.js Application

To run the Next.js application, use the following command:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### Hardhat Configuration

This repository includes a basic Hardhat configuration. To deploy the `Greeter` contract, follow these steps:

1. Compile the contracts:

   ```bash
   npx hardhat compile
   ```

2. Deploy the contracts:

   ```bash
   npx hardhat run scripts/deploy.js --network localhost
   ```

### Additional Notes

- Ensure you have a local Ethereum node running (e.g., using `npx hardhat node`).
- Customize the Hardhat configuration and scripts as needed for your project.

## Conclusion

This setup provides a starting point for integrating a Next.js 14 application with Hardhat for smart contract development and deployment.
