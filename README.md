# ETH Balance Exporter for Prometheus

This is a simple Python Flask application that acts as a Prometheus exporter to retrieve and expose the balance of a Ethereum (ETH) wallet. The balance is fetched from EthScan using the EthScan API and provided as a metric accessible via an HTTP endpoint.

## Prerequisites

- Python 3.9 or later
- Docker (optional, for containerization)

## Getting Started

1. Clone this repository:

   ```bash
   git clone git@github.com:fariborzsaffari/seed-ether-exporter.git
   cd src/
