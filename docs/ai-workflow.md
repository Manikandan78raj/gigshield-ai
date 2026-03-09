# AI Workflow – GigShield AI

## Step 1: Worker Registration
Delivery partner registers with details such as:
- Name
- Location
- Delivery Platform
- Weekly Income

This data is used for risk profiling.

## Step 2: AI Risk Assessment
An AI model evaluates risk based on:
- Historical weather patterns
- Pollution levels
- Flood-prone zones
- Traffic congestion

Output:
Risk Score for that delivery zone.

## Step 3: Dynamic Premium Calculation
Based on the risk score, the system calculates the weekly premium.

Example:
Low Risk → ₹20/week  
Medium Risk → ₹35/week  
High Risk → ₹50/week

## Step 4: Policy Activation
Worker activates the insurance policy by paying the weekly premium.

## Step 5: Real-Time Disruption Monitoring
External APIs monitor conditions such as:
- Rainfall
- Temperature
- Pollution

## Step 6: Parametric Trigger
If a disruption threshold is exceeded (example rainfall > 50mm), the system automatically triggers a claim.

## Step 7: Fraud Detection
AI checks for suspicious claims using anomaly detection.

Checks include:
- GPS location validation
- Weather data verification
- Duplicate claim detection

## Step 8: Instant Payout
Once validated, the payout is automatically credited to the worker.
