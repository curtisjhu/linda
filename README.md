# LINDA - (Lazy INtelligent Distributed Agents)
Currently, this is just a trading engine.
- We use Alpaca API, Schwab API to source market data and submit trades.
- Currently using Conditional Normalizing Flows to predict some market trends

The hope is that we will eventually transition over to using AI agents to source these trends for us.

## Getting Started
While most of this was built from first principles ground up, some the resulting fruit can be seen deployed from Google Cloud Batch Run

[linda.funnyscar.com](https://linda.funnyscar.com)

## Project Directory Structure
Subservers
- `pengine/account` - updates account activity
- `pengine/crypto` - crypto streaming and strategies
- `pengine/stock` - stock streaming and strategies
- `pengine/server` - public facing server displaying details
