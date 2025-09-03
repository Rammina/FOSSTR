# FOSSTR

**FOSSTR (Foster Care Support & Tracking Resource)** is an open-source platform designed to improve foster care systems by:

* Matching children with foster families.
* Connecting child welfare needs (clothing, school supplies, therapy, services) with foster parents and community supporters.
* Streamlining case management for social workers through secure, role-based access.

---

## Features

### For Social Workers

* Create and manage child profiles.
* Track placement status.
* Post and manage child welfare needs.

### For Foster Parents

* Create and update family profiles.
* Respond to placement requests.
* View and support posted needs.

### For Community Supporters

* Browse available child welfare needs.
* Fulfill or pledge to support specific needs.

### Cross-Cutting Features

* Role-based login and authentication.
* Secure in-app messaging.
* Basic dashboard with placement and needs overview.

---

## Tech Stack

* **Frontend:** React or Next.js
* **Backend:** Node.js 
* **Database:** PostgreSQL
* **Authentication:** JWT or OAuth2 with role-based permissions

---

## Project Goals

* Deliver a minimum viable product (MVP) that addresses the core workflows of foster care systems.
* Ensure data security and privacy for sensitive child welfare information.
* Build a scalable, open-source foundation that can be adapted by agencies, NGOs, and communities.

---

## Getting Started

### Prerequisites

* Node.js 
* React
* PostgreSQL installed and running.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Rammina/fosstr.git
   cd fosstr
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up environment variables:

   * Database connection string
   * JWT/OAuth2 secret keys

4. Run the development server:

   ```bash
   npm run dev
   ```

---

## Contributing

We welcome contributions from developers, social workers, foster parents, and community members.

* Open issues to suggest features or report bugs.
* Submit pull requests for improvements.
* Share feedback to shape the platform.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
