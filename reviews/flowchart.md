```mermaid
flowchart LR
    A[Customer] --> B{QR Scan}
    B -->|Dine-In| C[POS Terminal]
    B -->|Delivery| D[Swiggy/Zomato]
    C --> E[Kitchen Display]
    D --> E
    E --> F[Food Prepared]
```
