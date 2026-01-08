```mermaid
flowchart TD
  Start([Start]) --> A[Lecturer/Admin Log In]
  A --> B[Select Course and Class Management]
  B --> C["Choose Action (Create/Update)"]
  C --> D[Enter Course/Class Details]
  D --> E{Data Valid?}

  E -- NO --> F[Display Error Message]
  F --> D

  E -- YES --> G[(Save to Database])
  G --> H[Display Confirmation]
  H --> End([End])
```
