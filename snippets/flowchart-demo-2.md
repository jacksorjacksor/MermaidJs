```mermaid
flowchart TD
    A([Do something])
    B{Was it fun?}
    C[Yay!]
    D([Do something else])

    A
    A --> B
    B -- Yes -->C
    B -- No -->D
    D-->B
```

