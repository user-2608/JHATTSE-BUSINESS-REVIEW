flowchart TD
    A[Customer] -->|QR Scan| B(Jhattse POS)
    A -->|Walk-In| B
    A -->|Online Order| C[Food Aggregators]
    C -->|Zomato/Swiggy| B
    
    subgraph Jhattse Business
        B --> D{Order Processing}
        D -->|Dine-In| E[Kitchen Display System]
        D -->|Takeaway| F[Packaging Station]
        D -->|Delivery| G[Delivery Management]
        
        E --> H[Food Preparation]
        F --> H
        G --> H
        
        H --> I[Order Fulfillment]
        I -->|Dine-In| J[Table Service]
        I -->|Takeaway/Delivery| K[Handoff]
        
        J --> L[Payment]
        K --> L
        
        L --> M[Billing & GST Invoice]
        M --> N[Inventory Update]
        N --> O[Recipe Costing]
        O --> P[Waste Tracking]
        P --> Q[Analytics Dashboard]
    end
    
    L -->|Payment Methods| R[Payment Gateways]
    R -->|Paytm/PhonePe| S[Bank Settlement]
    
    Q --> T[Owner Reports]
    Q --> U[Staff Performance]
    Q --> V[Customer Insights]
    
    T --> W[Menu Optimization]
    U --> X[Incentive Calculation]
    V --> Y[Personalized Marketing]
