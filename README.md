# AI-Powered Parametric Insurance for Gig Workers

## Problem
Gig workers lose income due to external disruptions like weather, pollution, and curfews.

## Solution
An AI-powered insurance system that:
- Detects disruptions
- Automatically triggers claims
- Provides instant payouts

## Features
- AI Risk Assessment
- Fraud Detection
- Weekly Pricing Model
- Real-time Trigger Monitoring

## Tech Stack
- Frontend: React
- Backend: Node.js
- Database: MongoDB

## Status
Phase 1 – Ideation
## Parametric Triggers

- Rainfall > 50mm → Worker cannot operate → Claim triggered
- AQI > 300 → Unsafe environment → Claim triggered
- Curfew / Zone closure → Delivery halted → Claim triggered
## Weekly Pricing Logic

Premium is calculated based on:
- Area risk score
- Historical weather data
- Frequency of disruptions

Example:
- Low risk → ₹20/week
- Medium risk → ₹30/week
- High risk → ₹40/week
## AI Integration

- Predict risk using historical weather + location data
- Adjust weekly premium dynamically
- Detect fraud using anomaly detection (GPS mismatch, repeated claims)
