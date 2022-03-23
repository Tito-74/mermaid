```mermaid
flowchart TB
% color definition
classDef gray fill:#62524F, color:#fff
subgraph publicUser[ ]
    A1[[Public User<br/> Via REST API]]
    B1[Backend Services/<br/>frontend services]
end
% Apply the color to subgraph and A1
class publicUser,A1 gray