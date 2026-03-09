# System Architecture

GigShield AI Architecture

Worker Web App (React)
        │
        ▼
Backend API (Node.js)
        │
 ┌──────┼──────────┐
 ▼      ▼          ▼
Risk AI  Fraud AI  Trigger Engine
Model    Detection Weather API
        │
        ▼
      MongoDB
        │
        ▼
 Payment Gateway Simulation
