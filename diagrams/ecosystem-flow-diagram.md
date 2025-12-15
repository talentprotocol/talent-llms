# Talent Protocol - Ecosystem Flow

```mermaid
graph TB
    E[Ecosystems]
    T[Talent App]
    TR[Traders]
    P[Professionals]
    
    T -->|builder<br/>attention| E
    E -->|rewards| T
    
    TR -->|capital| T
    T -->|builder<br/>data| TR
    
    P -->|opportunities| T
    T -->|builder<br/>data| P
    
    style E fill:#fff,stroke:#000,stroke-width:3px,color:#000
    style T fill:#000,stroke:#000,stroke-width:3px,color:#fff
    style TR fill:#fff,stroke:#ccc,stroke-width:2px,color:#666
    style P fill:#fff,stroke:#ccc,stroke-width:2px,color:#666
```

## Flow Description

### 1. Ecosystems
- **Input**: Builder attention (discovery, engagement)
- **Output**: Rewards to builders via Talent App

### 2. Traders
- **Input**: Capital investment
- **Output**: Access to builder data for conviction

### 3. Companies / Recruiters
- **Input**: Builder data access
- **Output**: Opportunities (jobs, contracts, partnerships)

### Central Hub: Talent App
The platform aggregates builder reputation data and facilitates flows between all participants.
