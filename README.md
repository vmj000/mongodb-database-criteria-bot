# MongoDB Database Criteria Bot

A static flowchart chatbot that helps evaluate whether MongoDB is the right database fit for your project. Answer a series of guided questions and receive a scored recommendation.

## Live Demo

[https://vmj000.github.io/mongodb-database-criteria-bot/](https://vmj000.github.io/mongodb-database-criteria-bot/)

## Scorecard

| Score | Fit Level |
|-------|-----------|
| 7.5 - 10 | Strong fit for MongoDB |
| 6 - 7.5 | Good fit for MongoDB |
| 3 - 5.5 | Equal fit (MongoDB or Relational) |
| 0 - 2.5 | Weak fit - consider Relational |

## Question Flow

```
Q1: Project Type
   New service ────> Q2: Business Value > Q3: Business Requirements > Q4: Data & Domain > Q5: Dev Velocity > Q6: Platform Needs > Scorecard
   Refresh ────────> Q1b: Refresh Drivers > Q2 > Q3b: Target Architecture > Q4 > Q5 > Q6 > Scorecard
```

## Categories Evaluated

- **Project Type** - New vs refresh, legacy dependencies
- **Refresh Drivers** - Schema rigidity, bottlenecks, availability, compliance
- **Business Value** - Digital UX, latency, microservices, transactions
- **Business Requirements** - DDD, real-time, AI/agentic, operational data layer
- **Data & Domain** - Regulatory changes, temporal data, document model fit, aggregations
- **Developer Velocity** - DevOps independence, delivery speed
- **Platform Consolidation** - Search, vector, streaming on a single platform

## Usage

Open `index.html` in any browser. No dependencies, no build step — pure HTML/CSS/JS.
