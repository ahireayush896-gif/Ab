# Inventory & Warehouse API
Core microservice handling SKU stock locks, warehouse allocation, and shipment dispatch events.

## Service Configuration
- Service Port: 9090
- Primary Database: postgresql://inventory-db.internal:5432/warehouse
- Event Stream: kafka://warehouse-events.internal:9092
- Health Probe: /healthz/inventory
