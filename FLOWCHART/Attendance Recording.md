```mermaid
flowchart TD
    Start([Start]) --> A[Lecturer Log In]
    A --> B[Select Course and Class]
    B --> C[Select Attendance Method Manual/QR/Online]
    C --> D[Record Attendance]
    D --> E[Save Attendance to Database]
    E --> F[Display Confirmation]
    F --> End([End])
```
