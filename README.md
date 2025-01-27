# Notesheet Tracker

The **Notesheet Tracker** is a comprehensive platform designed to streamline the management and approval process of financial notesheets for clubs and fests at **Indian Institute of Technology, Patna (IIT Patna)**. This system ensures transparency, efficiency, and accountability by enabling the creation, customization, approval, and tracking of financial notesheets through a structured workflow.

### Key Features

-   **Templates for Notesheets**:

    -   **Reimbursement**: Submit requests for reimbursement of personal expenses incurred during an event.
    -   **Disbursement**: Request advance funds for an upcoming event.
    -   **Settlement**: Finalize and settle all expenses and bills after an event concludes.

-   **Approval Workflow**:
    Notesheets pass through a predefined sequence of approvals:

    1. General Secretary (GenSec)
    2. Vice President Gymkhana (VP)
    3. ARSA/DRSA
    4. President Gymkhana
    5. Payment In Charge (PIC)
    6. Associate Dean (ADean)
       Each approver can either forward the notesheet with their comments or reject it with reasons.

-   **Customizable Notesheets**:
    Clubs and fests can use pre-designed templates or upload their own PDFs to create notesheets.

-   **Reminders for Pending Tasks**:
    Automated daily reminders for pending approvals to ensure timely processing.

-   **Full Audit History**:
    Every individual involved in the approval chain can view the complete history of their actions, including dates and comments, with the ability to download notesheets as PDFs.

-   **Digital Signatures**:
    Forwarded notesheets include verifiable digital signatures for authenticity.

-   **Expense Tracker**:
    -   Clubs can view their expenditures.
    -   GenSec can view club-specific data.
    -   Admins and higher authorities can view a categorized overview of all expenditures.

---

## Login Credentials and User Roles

To access the system, use the following login credentials:

-   **Username**: `gensectech@iitp.ac.in`
-   **Password**: `qwertTyuio@p12345`

Upon logging in as the **General Secretary (GenSec)**, the user will have the following roles and permissions:

-   **Reject Notesheet**: GenSec has the authority to reject raised notesheets for different technical clubs, providing comments on the rejection.
-   **Approve Notesheet for Further Approval**: GenSec can approve notesheets for further processing by forwarding them to the next level in the approval chain.

-   **Raise Notesheets**: GenSec can create and submit notesheets (Reimbursement, Disbursement, and Settlement) for their respective clubs or fests.

---

## Installation Guide

To set up the project, install all dependencies from the root directory:

```bash
npm run install-all
```

This command installs dependencies for both the client and server.

## Running Guide

To start the development environment, run the following command from the root directory:

```bash
npm run dev
```

This will launch both the client and server concurrently. The application will be accessible at:

-   **Client**: [http://localhost:3000](http://localhost:3000)
-   **Server**: [http://localhost:8000](http://localhost:8000)

To start either the client or server individually:

```bash
# Start the client
npm run client

# Start the server
npm run server
```

---

## Production Guide

Run the application in production mode from the root directory with:

```bash
npm start
```

This starts both the client and server in a production environment.

---

## Tech Stack

-   **Frontend**: [Next.js](https://nextjs.org/) with [Tailwind CSS](https://tailwindcss.com/)
-   **Backend**: [Node.js](https://nodejs.org/) with [Express](https://expressjs.com/)
-   **Database**: [MongoDB](https://www.mongodb.com/) with [Mongoose](https://mongoosejs.com/)

---

## Temporary Link

Since the application is in the testing stage, you can access it temporarily at:

**[http://testing-notesheet-tracker.example.com](http://testing-notesheet-tracker.example.com)**
