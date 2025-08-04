# 🛡️ Wallet Audit DB

A modular backend + frontend system for tracking wallet activity, audit reports, and token metadata across chains.

## 🔧 Tech Stack

- **Frontend**: React + Vite
- **Backend**: FastAPI + MongoDB
- **Wallets**: OKX, MetaMask, SafePal, Phantom
- **Audit Sources**: De.Fi Express Audit, manual submissions

## 📦 Features

- Dynamic API endpoints for audit and token data
- Wallet-based login and NFT gallery integration
- TON wallet campaign tracking
- Admin review flow for submissions
- NFT minting tied to ledger events

## 🚀 Getting Started

```bash
# Backend
cd backend
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload

# Frontend
cd frontend
npm install
npm run dev

