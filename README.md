# Inventory & Warehouse API
Core microservice handling SKU stock locks, warehouse allocation, and shipment dispatch events.

## Service Configuration
- Service Port: 9090
- Primary Database: postgresql://inventory-db.internal:5432/warehouse
- Event Stream: kafka://warehouse-events.internal:9092
- Health Probe: /healthz/inventory

# Order & Checkout API
Core microservice handling shopping carts, tax calculation, and order confirmation webhooks.

## Service Configuration
- Service Port: 8080
- Primary Database: postgresql://orders-db.internal:5432/checkout
- Cache Layer: redis://cart-cache.internal:6379/0
- Health Probe: /healthz/orders
