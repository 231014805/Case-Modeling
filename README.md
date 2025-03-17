graph TD
    A[Student] -->|Books| B[Counseling Session]
    A -->|Manages| C[Profile]
    A -->|Provides| D[Feedback]
    B -->|Conducts| E[Counselor]
    E -->|Manages| F[Availability]
    E -->|Reviews| D
    G[Administrator] -->|Manages| H[User Accounts]
    G -->|Generates| I[Reports]
    G -->|Configures| J[System Settings]
    A -->|Receives| K[Notifications]
    E -->|Receives| K
    A -->|Cancels| B
    A -->|Reschedules| B
flowch#
