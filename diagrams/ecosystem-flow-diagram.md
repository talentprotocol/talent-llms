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
    T -->|verified<br/>builders| P
    
    style E fill:#fff,stroke:#000,stroke-width:3px,color:#000
    style T fill:#000,stroke:#000,stroke-width:3px,color:#fff
    style TR fill:#fff,stroke:#ccc,stroke-width:2px,color:#666
    style P fill:#fff,stroke:#ccc,stroke-width:2px,color:#666
```

## Flow Description

### 1. Central Hub: Talent App
- Aggregates builder reputation data and facilitates flows between all participants.

### 3. Ecosystems
- **Input**: Builder attention (discovery, engagement)
- **Output**: Rewards to builders via Talent App

### 3. Traders
- **Input**: Capital investment
- **Output**: Access to aggreagated builder data for conviction

### 4. Professionals
- **Input**: Curation of verified builders
- **Output**: Opportunities (jobs, contracts, partnerships)
