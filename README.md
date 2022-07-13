```mermaid
flowchart TD
  A[Should I go to work?] --> B[Is it Saturday?];
  B -- Yes --> C[Don't go to work];
  B -- No --> D[Is it Sunday?];
  D -- Yes --> C;
  D -- No --> E[Go to work];
```
