# FT-3 DeFi RL - Reinforcement Learning for DeFi Portfolio Management

## Overview
FastAPI-based REST API for training and managing DeFi portfolios using reinforcement learning with global tax optimization.

## Quick Start

### Install Dependencies
pip install -r requirements.txt

### Run Server
python3 api_server.py

Server runs on http://localhost:8000

## API Endpoints

### Status
- GET /api/status - Portfolio metrics and training status

### Portfolio Management
- GET /api/category-stocks/{category} - Get recommended stocks
- POST /api/validate-allocation - Validate 85% accuracy
- POST /api/rebalance-plan - Get rebalancing trades

### Tax Calculator
- GET /api/tax-rates - All country tax rates
- GET /api/tax-country/{country} - Specific country tax info

### Training
- POST /api/start-training - Start RL training
- POST /api/stop-training - Stop training

## Features
✅ Real-time stock data (Yahoo Finance)
✅ Multi-country tax calculator
✅ Portfolio allocation validator
✅ RL training loop
✅ REST API with CORS

## Author
Lalith Praveen

## License
MIT
