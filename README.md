# mutpAPIS
# Aave WBTC Lending API

This project provides an API for automating the process of depositing Wrapped Bitcoin (WBTC) into the Aave lending protocol and calculating the amount that can be borrowed against the deposited collateral.

## Features

- Deposit WBTC into Aave for lending.
- Calculate the amount that can be borrowed based on the deposited collateral.
- RESTful API endpoints for easy integration.

## Project Structure

```
aave-wbtc-lending-api
├── src
│   ├── app.ts                  # Entry point of the application
│   ├── controllers
│   │   └── lendingController.ts # Handles lending operations
│   ├── routes
│   │   └── lendingRoutes.ts     # Defines API endpoints
│   ├── services
│   │   └── aaveService.ts       # Interacts with Aave protocol
│   ├── utils
│   │   └── calculation.ts        # Utility functions for calculations
│   └── types
│       └── index.ts             # TypeScript interfaces and types
├── package.json                 # npm configuration file
├── tsconfig.json                # TypeScript configuration file
└── README.md                    # Project documentation
```

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd aave-wbtc-lending-api
   ```
3. Install the dependencies:
   ```
   npm install
   ```

## Usage

1. Start the application:
   ```
   npm start
   ```
2. The API will be available at `http://localhost:3000`.

## API Endpoints

- **POST /deposit**: Deposit WBTC into Aave.
- **GET /borrowable-amount**: Calculate the amount that can be borrowed based on the deposited collateral.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.
