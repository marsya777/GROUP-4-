```flowchart TD
    Start([Start]) --> A[Display Login Page]
    A --> B[/Enter Username and Password/]
    B --> C[Validate Credentials]
    C --> D{Credentials Valid?}
    
    D -- NO --> E[Display Error Message]
    E --> B
    
    D -- YES --> F[Determine User Role]
    F --> G[Load Role-Based Dashboard]
    G --> End([End])
```
