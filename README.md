# Go Gateway Payments

A robust payment gateway service implemented in Go, providing secure and scalable payment processing capabilities.

## Features

- Secure payment processing
- Multiple payment method support
- Transaction management
- Error handling and logging
- API documentation
- Scalable architecture

## Prerequisites

- Go 1.21 or higher
- Docker (optional, for containerization)
- Make (optional, for using Makefile commands)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/gilbertopsantosjr/go-gateway-payments.git
   cd go-gateway-payments
   ```

2. Install dependencies:
   ```bash
   go mod download
   ```

3. Build the project:
   ```bash
   make build
   ```

## Project Structure

```
.
├── cmd/                 # Application entrypoints
├── internal/            # Private application code
│   ├── api/            # API handlers
│   ├── config/         # Configuration
│   ├── domain/         # Domain models
│   ├── repository/     # Data access layer
│   └── service/        # Business logic
├── pkg/                # Public libraries
├── scripts/            # Build and deployment scripts
└── test/              # Test files
```

## Getting Started

To start working on this project:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.