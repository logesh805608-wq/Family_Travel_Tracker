# Family Travel Tracker

A multi-user web application built with Node.js, Express, and PostgreSQL that allows family members to track, manage, and visualize the countries they have visited.

## 🚀 Features

* Multi-User Profiles: Switch between different users to view individual travel histories, complete with custom color themes.
* Add New Users: Create custom profiles with custom names and color preferences (such as teal, powderblue, etc.).
* Country Tracking: Input and record visited countries, automatically mapping country names to official country codes.
* Duplicate Prevention: Robust database constraints and handling (ON CONFLICT) to prevent duplicate entries per user.
* Interactive Visualization: Dynamic rendering using EJS and PostgreSQL integration.

## 🛠️ Tech Stack

* Runtime: Node.js
* Framework: Express.js
* Templating Engine: EJS
* Database: PostgreSQL (pg)
* Environment Management: dotenv
* Middleware: Body-Parser

## 📦 Getting Started

### Prerequisites
Make sure you have Node.js and PostgreSQL installed on your machine.

### Installation & Setup

1. Clone the repository or open your project folder.
2. Install the required dependencies:
   npm install

3. Create a .env file in the root directory and configure your PostgreSQL database credentials:
   PG_USER=your_postgres_user
   PG_HOST=localhost
   PG_DATABASE=your_database_name
   PG_PASSWORD=your_postgres_password
   PG_PORT=5432

4. Start the application using Nodemon:
   nodemon index.js

5. Open your browser and navigate to http://localhost:3000.