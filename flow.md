```mermaid
graph TD;
    A[Initialize Population] --> B[Evaluate Fitness];
    B --> C[Select Parents];
    C --> D[Crossover];
    D --> E[Mutate Offspring];
    E --> F[Evaluate Fitness];
    F --> G[Select Survivors];
    G --> H[Check Termination];
    H --> I[Yes];
    H --> |No| B;
    I --> J[Output Best Solution];
