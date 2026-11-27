# Payments & Fraud Gateway API
Unified microservice handling payment authorizations, risk scoring, and settlement reconciliation.

## Service Configuration
- Service Port: 8095
- Primary Database: postgresql://payments-db.internal:5432/gateway
- Event Stream: kafka://payments-events.internal:9092
- Cache Layer: redis://fraud-cache.internal:6379/1
- Health Probe: /healthz/payments
