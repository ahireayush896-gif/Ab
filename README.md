# Order & Checkout API
Core microservice handling shopping carts, tax calculation, and order confirmation webhooks.

## Service Configuration
- Service Port: 8080
- Primary Database: postgresql://orders-db.internal:5432/checkout
- Cache Layer: redis://cart-cache.internal:6379/0
- Health Probe: /healthz/orders
