```mermaid
flowchart TD
  A[Go to work] --> B[Is it Saturday?];
  B -- Yes --> C[Don't go to work];
  B -- No --> D[Is it Sunday?];
  D -- Yes --> C;
  D -- No --> E[Don't go to work];
```
