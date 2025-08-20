```mermaid
flowchart LR
    F["Finance"]

    %% Channels
    A["Capital Accumulation"]
    B["Capital Productivity"]
    C["Technological Innovation"]

    %% Subtitles (Financial Repression Effects)
    A_sub["FR Effects: ↓ Savings & Investment • ↑ Reserve Requirements • Credit Misallocation"]
    B_sub["FR Effects: Distorted Allocation • Monopolistic Banking • Informal Markets • Mispriced Signals"]
    C_sub["FR Effects: ↓ Innovation Funding • Capital Controls • Weak VC/PE • Informal Finance"]

    %% Flow connections
    F --> A --> G["Economic Growth"]
    F --> B --> G
    F --> C --> G

    %% Sub connections
    A --- A_sub
    B --- B_sub
    C --- C_sub

```
