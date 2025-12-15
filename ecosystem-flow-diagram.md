# Talent Protocol - Ecosystem Flow

```mermaid
graph TB
    subgraph "1. Ecosystems"
        E[Ecosystems]
    end
    
    subgraph "Central Platform"
        T[Talent App]
    end
    
    subgraph "2. Traders"
        TR[Traders]
    end
    
    subgraph "3. Companies / Recruiters"
        C[Companies /<br/>Recruiters]
    end
    
    E -->|builder<br/>attention| T
    E -->|rewards| T
    
    T -->|capital| TR
    T -->|builder<br/>data| TR
    
    T -->|opportunities| C
    T -->|builder<br/>data| C
    
    style E fill:#000,stroke:#000,stroke-width:3px,color:#fff
    style T fill:#000,stroke:#000,stroke-width:3px,color:#fff
    style TR fill:#fff,stroke:#ccc,stroke-width:2px,color:#666
    style C fill:#fff,stroke:#ccc,stroke-width:2px,color:#666
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
