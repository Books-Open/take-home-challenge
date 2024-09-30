# Take-Home Challenge: Appointment Booking System

## Objective
Build a simple appointment booking system with both back-end and front-end components. The system should allow users to select a date and time slot, enter their information, and confirm an appointment. Upon confirmation, an email should be sent to the client.

## Requirements

### Back-End
-   **API**: Must be built using NestJS.
-   **Endpoints**:
  - `POST /appointments`: Creates a new appointment with the client’s information.

### Front-End
-   **Appointment Form**:
  - Allow the user to select a date and time slot.
  - Collect basic information from the client (first name, last name, email address, phone number).
  - Send a request to the `POST /appointments` endpoint to create the appointment.
-   **Confirmation Page**:
  - Display the details of the confirmed appointment.
  - Ensure an email is sent to the client confirming the appointment.

## Instructions

1. **Back-End**:
   - Implement the `POST /appointments` endpoint as described above.
   - Ensure the API is capable of handling the required operations.

2. **Front-End**:
   - Implement the appointment form to collect client information and confirm the appointment.
   - Display a confirmation page with the appointment details.

3. **Email Notification**:
   - Upon appointment creation, send a confirmation email to the client.
   - Note: You can use any email service (e.g., Resend, Sendgrid, AWS SES) to send the email.

## Submission
-   Create a **private** GitHub repository for your project.
-   Include a README file with:
  - Instructions on how to set up and run the project locally.
  - A brief description of the project and its features.
  - Any assumptions made and areas for potential improvement.
-   Optionally, include a short video walkthrough (using Loom or a similar tool) demonstrating the functionality of the application.
-   Invite the following GitHub users to your repository:
  - [@joaopcm](https://github.com/joaopcm)
  - [@ivoneijr](https://github.com/ivoneijr)

## Evaluation Criteria
-   **Technical Skills**: Proficiency in building APIs and front-end applications.
-   **Problem-Solving**: Approach to handling requirements and constraints.
-   **Code Quality**: Clean, readable, and maintainable code.
-   **Performance**: Efficient API and front-end performance.
-   **Communication**: Clarity and completeness of the README file and optional video walkthrough.

## Getting Started
### Prerequisites
-   Node.js
-   PostgreSQL (if using a relational database)
-   Any email service for sending confirmation emails

## Contact

If you have any questions, feel free to reach out to us at [hiring@booksopen.app](mailto:hiring@booksopen.app).

Good luck, and we look forward to seeing your submission!