### User Stories Table

| Story ID | User Story                                                                                       | Acceptance Criteria                                                                                      | Priority |
|----------|--------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|----------|
| US001    | As a student, I want to register for an account so that I can access counseling services.        | Registration form accepts valid inputs; confirmation email sent upon successful registration.            | High     |
| US002    | As a student, I want to log in securely so that my personal information is protected.            | Login requires valid credentials; account locks after 3 failed attempts.                                 | High     |
| US003    | As a student, I want to book a counseling session so that I can receive timely support.          | Booking system displays available slots; confirmation provided upon successful booking.                  | High     |
| US004    | As a student, I want to cancel a counseling session so that I can manage my schedule effectively. | Cancellation option available up to 24 hours before the session; confirmation of cancellation provided.   | Medium   |
| US005    | As a counselor, I want to manage my availability so that students can book sessions accordingly.  | Interface to set available time slots; updates reflected in the student booking system.                   | High     |
| US006    | As a counselor, I want to view feedback from students so that I can improve my services.         | Feedback accessible after session completion; aggregated feedback reports available.                     | Medium   |
| US007    | As an administrator, I want to manage user accounts so that the system maintains integrity.      | Admin panel to activate/deactivate accounts; audit trail of account changes maintained.                  | High     |
| US008    | As an administrator, I want to generate usage reports so that I can monitor system performance.  | Reports include metrics on session bookings, cancellations, and user activity; exportable in CSV format. | Medium   |

### Product Backlog

| Story ID | User Story                                                                                      | Priority    | Effort Estimate | Dependencies | Justification                                                                                           |
|----------|-------------------------------------------------------------------------------------------------|-------------|-----------------|--------------|----------------------------------------------------------------------------------------------------------|
| US001    | As a student, I want to register for an account so that I can access counseling services.       | Must-have   | 3               | None         | Essential for accessing the system.                                                                      |
| US002    | As a student, I want to log in securely so that my personal information is protected.           | Must-have   | 2               | US001        | Ensures data security and user authentication.                                                           |
| US003    | As a student, I want to book a counseling session so that I can receive timely support.         | Must-have   | 5               | US002        | Core functionality for service delivery.                                                                 |
| US004    | As a student, I want to cancel a counseling session so that I can manage my schedule effectively.| Should-have | 2               | US003        | Enhances user flexibility and system usability.                                                          |
| US005    | As a counselor, I want to manage my availability so that students can book sessions accordingly. | Must-have   | 3               | None         | Facilitates accurate session scheduling.                                                                 |
| US006    | As a counselor, I want to view feedback from students so that I can improve my services.        | Could-have  | 2               | US003        | Supports continuous improvement based on user feedback.                                                  |
| US007    | As an administrator, I want to manage user accounts so that the system maintains integrity.     | Must-have   | 4               | None         | Critical for system security and user management.                                                        |
| US008    | As an administrator, I want to generate usage reports so that I can monitor system performance. | Should-have | 3               | US007        | Assists in evaluating system effectiveness and identifying areas for improvement.                         |

### Sprint Backlog

| Task ID | Task Description                                             | Assigned To | Estimated Hours | Status  |
|---------|--------------------------------------------------------------|-------------|-----------------|---------|
| T001    | Develop user registration form and backend integration.      | Dev Team    | 8               | To Do   |
| T002    | Implement secure login functionality with session management.| Dev Team    | 6               | To Do   |
| T003    | Create counselor availability management interface.          | Dev Team    | 7               | To Do   |
| T004    | Develop session booking system for students.                 | Dev Team    | 10              | To Do   |
| T005    | Set up admin panel for user account management.              | Dev Team    | 9               | To Do   |
