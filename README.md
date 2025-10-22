# Library Card System

A blockchain-based library card system for public libraries managing patron registration, book checkouts, and inter-library lending coordination.

## Overview

Library Card System digitalizes library patron management using blockchain technology, providing secure patron registration, book checkout tracking, and seamless inter-library lending coordination.

## Real-Life Use Case

Public libraries manage patron accounts and book lending. This system provides digital card management, checkout tracking, and inter-library lending coordination, making it easier for patrons to access materials across multiple libraries.

## Features

### Patron Management
- Register and manage library card holders
- Track patron borrowing history and status
- Manage patron fines and holds
- Handle card renewals and replacements

### Book Checkout System
- Track book checkouts and returns
- Monitor due dates and overdue items
- Calculate and manage late fees
- Reserve system for popular titles

### Inter-Library Lending
- Coordinate book transfers between libraries
- Track lending agreements
- Manage return logistics
- Share catalog information

### Administrative Tools
- Generate circulation reports
- Monitor inventory status
- Track collection usage
- Analyze borrowing patterns

## Smart Contract: library-manager

The `library-manager` contract manages all library operations with capabilities including patron registration, checkout tracking, inter-library lending, and administrative functions.

## Technical Stack

- **Blockchain**: Stacks blockchain
- **Smart Contract Language**: Clarity  
- **Development Framework**: Clarinet
- **Storage**: On-chain data storage

## Getting Started

### Prerequisites
- Clarinet CLI installed
- Node.js and npm
- Git

### Installation

```bash
git clone https://github.com/sholepeter8/library-card-system.git
cd library-card-system
npm install
```

### Testing

```bash
clarinet check
clarinet test
```

## Contract Functions

### Public Functions
- `register-patron`: Register new library card holder
- `checkout-book`: Process book checkout
- `return-book`: Process book return
- `request-interlibrary-loan`: Request book from another library
- `update-patron-status`: Update patron account status

### Read-Only Functions
- `get-patron-info`: Get patron details
- `get-checkout-record`: Get checkout information
- `calculate-fines`: Calculate overdue fines
- `check-availability`: Check book availability
- `get-lending-stats`: Get inter-library lending statistics

## Security

- Only authorized librarians can modify records
- Immutable checkout history
- Secure patron data management
- Fine calculation transparency

## License

MIT License

## Acknowledgments

Built with Clarity on the Stacks blockchain for transparent and efficient library management.
