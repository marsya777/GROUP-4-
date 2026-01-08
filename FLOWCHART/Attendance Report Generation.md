```mermaid
flowchart TD
  Start([Start]) --> A[Lecturer/Admin Log In]
  A --> B[Select Generate Report]
  B --> C[Choose Report Type and Data]
  C --> D[Retrieve Attendance Data]
  D --> E[Generate Report]
  E --> F{Export Report}

  F -- NO --> G[Display On Screen]
  F -- YES --> H[Export as PDF/Excel]

  G --> End([End])
  H --> End
