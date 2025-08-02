# QuickDesk_Full_Project

# QuickDesk

[cite\_start]QuickDesk is a simple, easy-to-use help desk solution where users can raise support tickets, and support staff can manage and resolve them efficiently[cite: 5, 7]. [cite\_start]The system aims to streamline communication between users and support teams without unnecessary complexity[cite: 8].

## Features

### User Roles

The application supports three main user roles:

  * [cite\_start]**End Users (Employees/Customers):** Can create and track their tickets[cite: 10]. [cite\_start]They can also upvote & downvote the questions[cite: 26].
  * [cite\_start]**Support Agents:** Can respond to, view, assign, and resolve tickets[cite: 11, 22]. [cite\_start]They can also add comments/updates to tickets[cite: 24].
  * [cite\_start]**Admin:** Can manage users, categories, and the overall ticket flow[cite: 12].

### Core Functionality

  * [cite\_start]**Authentication:** Users should be able to register and log in to the system[cite: 14].
  * [cite\_start]**Ticket Creation:** Users can create a ticket with a subject, description, category, and an optional attachment[cite: 15].
  * [cite\_start]**Ticket Statuses:** Tickets progress through statuses: Open → In Progress → Resolved → Closed[cite: 23].
  * [cite\_start]**Dashboard:** Users can view the status of their submitted tickets[cite: 16]. [cite\_start]The dashboard includes search and filtering options[cite: 17].
  * [cite\_start]**Search & Filtering:** Users can filter to see open/closed tickets [cite: 18][cite\_start], see their own tickets only [cite: 19][cite\_start], or search based on category[cite: 20].
  * [cite\_start]**Sorting:** The system allows sorting based on most replied tickets or recently modified tickets[cite: 21].
  * [cite\_start]**Notifications:** Email notifications are sent when a ticket is created or its status changes[cite: 27].

## Technology Stack

### Backend

  * **Node.js & Express.js:** To build the RESTful API.
  * **MongoDB & Mongoose:** For data persistence.
  * **JWT:** For authentication.
  * **Nodemailer:** To handle email notifications.

### Frontend

  * **React:** For the user interface.
  * **Framer Motion:** For animations.
  * **Tailwind CSS:** For styling and responsiveness.
  * **Axios:** For API communication.

## Getting Started

### Prerequisites

  * Node.js and npm installed
  * MongoDB instance running

### Installation

1.  **Clone the repository:**

    ```bash
    git clone [repository-url]
    cd quickdesk
    ```

2.  **Backend Setup:**

    ```bash
    cd backend
    npm install
    ```

    Create a `.env` file and add your configuration variables.

3.  **Frontend Setup:**

    ```bash
    cd ../frontend
    npm install
    ```

### Running the Project

1.  **Start the Backend:**

    ```bash
    cd backend
    npm run dev
    ```

    The backend server will run on `http://localhost:5000`.

2.  **Start the Frontend:**

    ```bash
    cd frontend
    npm start
    ```

    The frontend application will open in your browser at `http://localhost:3000`.

## Evaluation Criteria

[cite\_start]The project was developed with a focus on several key criteria[cite: 49]:

  * [cite\_start]**Coding Standards:** Consistent naming, proper formatting, and clear, maintainable code[cite: 50, 51, 52, 53].
  * [cite\_start]**Logic:** Correctness of business logic and handling of edge cases[cite: 56, 57, 59].
  * [cite\_start]**Modularity:** Separation of concerns and a clean project structure[cite: 61, 62, 64].
  * [cite\_start]**Database Design:** A well-structured schema with clear relationships and efficient indexing[cite: 66, 67, 68].
  * [cite\_start]**Frontend Design:** An intuitive UI, consistent styling, and responsiveness[cite: 72, 73, 74].
  * [cite\_start]**Performance:** Efficient algorithms and avoidance of bottlenecks[cite: 78, 79, 80].
  * [cite\_start]**Scalability:** An architecture that supports growth and is extensible[cite: 84, 85, 89].
  * [cite\_start]**Security:** Input validation, secure authentication, and protection against common vulnerabilities[cite: 90, 91, 93].
  * [cite\_start]**Usability:** User-friendly navigation, clear error messages, and intuitive workflows[cite: 96, 97, 98].
