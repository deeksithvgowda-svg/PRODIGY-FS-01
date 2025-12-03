# Secure User Authentication System (Internship Project - Prodigy)

This project is a single-page, responsive web application (SPA) demonstrating a secure and modern authentication flow, developed as the core deliverable for the **Prodigy Infotech** internship.

This project is completely developed in Ubuntu OS and works best Ubuntu.The system is built entirely on the client-side using Vanilla JavaScript, simulating core backend security principles like token management and hashing.

##  Key Features & Technical Achievements

| Feature | Description | Technical Implementation |
| :--- | :--- | :--- |
| **Authentication Security** | Implements standard security mechanisms to protect user credentials and sessions. | **Password Hashing** (SHA-256 simulation) and **Token-Based Sessions** (JWT simulation for state management). |
| **Role-Based Access Control (RBAC)** | Strict authorization applied to protect sensitive views and data. | Restricts access to the **Admin Console** using the user's role payload extracted from the token. |
| **User Management** | Provides administrative privileges to view and delete user accounts. | **Admin Console** view with logic to prevent accidental deletion of the active admin account. |
| **Architecture (SPA)** | Built for performance and modern user experience. | Single-Page Application (SPA) architecture using **Vanilla JavaScript** for all hash-based routing (`#login`, `#dashboard`). |
| **UI/UX** | Professional, clean, and responsive design. | Styled with **Tailwind CSS**. Custom modal components are used for feedback, replacing native browser alerts/confirms. |

##  How to Run the Project

Since this is a client-side SPA, running the project is straightforward:

1.  **Clone the Repository:**
    ```bash
    git clone [Your Repository HTTPS Link Here]
    cd [your-repo-name]
    ```
2.  **Start the Server (Recommended Professional Method):**
    For a proper HTTP environment, use `http-server` (requires Node.js):
    ```bash
    npm install -g http-server
    http-server -p 3000
    ```
3.  **Access:** Open your browser and navigate to `http://localhost:3000`.

## Technology Stack

* **Language:** Vanilla JavaScript (ES6+)
* **Styling:** HTML5 & Tailwind CSS (Loaded via CDN)
* **Environment:** Node.js `http-server` (for local hosting)
* **Mock Database:** Browser `localStorage`

---
*Developed by **Deekshith gowda kv***
