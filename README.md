# Oshin Hotel Review Management Server

![Node.js](https://img.shields.io/badge/Node.js-v18%2B-green)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-blue)
![Express](https://img.shields.io/badge/Express-5.x-lightgrey)
![MongoDB](https://img.shields.io/badge/MongoDB-Mongoose-green)

A robust, multi-tenant backend system designed to manage hotel guest reviews, staff authentication, and advanced analytics. This server supports role-based access control (RBAC), guest token generation, and comprehensive reporting pipelines.

## 🚀 Key Features

* **Multi-Tenancy:** Supports multiple hotels via `hotelId` association.
* **Role-Based Access Control:** Granular permissions for Super Admins, Hotel Admins, Viewers, and Department Staff (`room`, `f&b`, `cfc`).
* **Analytics Engine:** Advanced aggregation pipelines for:
    * Daily/Monthly/Yearly breakdown.
    * Staff performance leaderboards.
    * Question-specific and Composite trend analysis.
    * Low-rated review tracking.
* **Guest Token System:** Secure, one-time-use tokens for gathering guest feedback.
* **Security:** Implements `helmet`, `cors`, `rate-limiting`, and `mongo-sanitize`.

---

## 🛠 Tech Stack

* **Runtime:** Node.js
* **Language:** TypeScript
* **Framework:** Express.js (v5.0+)
* **Database:** MongoDB (via Mongoose)
* **Authentication:** JWT (JSON Web Tokens)
* **Validation:** Express-Validator

---

## ⚙️ Prerequisites

Ensure you have the following installed on your server or local machine:

* [Node.js](https://nodejs.org/) (v18 or higher recommended)
* [npm](https://www.npmjs.com/) or yarn
* [MongoDB](https://www.mongodb.com/) (Atlas connection string recommended)

---
