```mermaid
flowchart TD
  A[Go to work] --> B[Is it Saturday?];
  B -- Yes --> C[Don't go to work];
  B -- No --> D[Is it Sunday?];
  D -- Yes --> E[Go to work];
  D -- No --> C;
```
