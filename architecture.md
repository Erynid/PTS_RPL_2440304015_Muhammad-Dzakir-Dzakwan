# Arsitektur System
- Layered Architecture (Three-Tier)
- Redis Cache & Object File Storage

## Performance Strategy
- In-Memory Caching (Redis) untuk pencarian status < 3 detik
- Separation of File Storage untuk menjaga ukuran DB
