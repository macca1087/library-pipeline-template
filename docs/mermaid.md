```mermaid
flowchart LR
    Source[Source data] --> Bronze[Bronze<br/>raw, as received]
    Bronze --> Silver[Silver<br/>cleaned and validated]
    Silver --> Gold[Gold<br/>business-ready]
    Gold --> Consumers[Reports and analytics]
```
