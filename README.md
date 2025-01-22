## Tracker App Overview

This is a **Tracker App** built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js) and **Apollo GraphQL**. The app allows users to track their expenses and investments, providing real-time insights through interactive charts powered by **Chart.js**.

<<<<<<< HEAD

![alt text](<Screenshot 2025-01-22 121232.png>) ![alt text](<Screenshot 2025-01-22 121353.png>) ![alt text](<Screenshot 2025-01-22 121412.png>) ![alt text](<Screenshot 2025-01-22 121614.png>) ![alt text](<Screenshot 2025-01-22 121826.png>) ![alt text](<Screenshot 2025-01-22 122153.png>) ![alt text](<Screenshot 2025-01-22 121117.png>) ![alt text](<Screenshot 2025-01-22 121157.png>)
![alt text](<Screenshot 2025-01-22 122035.png>) ![alt text](<Screenshot 2025-01-22 122121.png>) ![alt text](<Screenshot 2025-01-22 122153-1.png>)

=======
>>>>>>> d35540ddbb01f06963a11c7e70d2400237a77a78
### 🌟 **Tech Stack:**
- **MongoDB**: A NoSQL database used to store user data, including expense and investment details.
- **Express.js**: A lightweight web framework for building the backend server.
- **React.js**: A front-end library for building interactive and dynamic user interfaces.
- **Node.js**: A JavaScript runtime for the backend logic.
- **Apollo GraphQL**: A query language for the API that efficiently handles data fetching, mutations, and managing real-time updates.

### 📝 **GraphQL Schema and Resolvers**:
- **Type Definitions**: Define the structure of data, including types for expenses, investments, and user information.
- **Resolvers**: Implement the logic to fetch, update, or delete data from MongoDB. They handle queries and mutations in GraphQL to interact with the database.

### 🔄 **Mutations**:
- **Mutations** allow users to **add, update, or delete** their expense and investment data.
- Establish **graph relations** between users and their tracked data, ensuring data consistency and easy management.

### 🎃 **Authentication with Passport.js**:
- **Passport.js** is used to manage **user authentication** via **sessions**.
- The **MongoDB session store** ensures secure persistence of user sessions, allowing users to remain logged in across sessions.

### 🚀 **Global State Management with Apollo Client**:
- **Apollo Client** is used for managing the **global state** and communication between the front-end React app and the GraphQL API.
- It provides **caching** and **optimistic UI** to ensure the application remains fast and responsive while interacting with the backend.

### 🐞 **Error Handling**:
- **Server-side error handling** is done using **Apollo Server** to return specific error messages in GraphQL responses.
- **Client-side error handling** in React ensures that any issues with data fetching or mutations are communicated to the user.

### 📊 **Chart.js Integration**:
- **Chart.js** is used to visualize **live data** such as expenses and investments in the form of interactive charts.
- When a user adds or updates their data (expenses/investments), the charts automatically update on the dashboard to reflect the latest information.

### 💾 **MongoDB for Data Storage**:
- All user data, including **expense** and **investment records**, are securely stored in **MongoDB**.
- The **MongoDB schema** is defined in the GraphQL API to ensure proper data validation and structure.

### 🔄 **Real-Time Data Updates**:
- When users input new data or make changes to existing records, the dashboard automatically **updates** in real-time using **Apollo Client** and GraphQL subscriptions, keeping the data and charts in sync.

### **Features**:
- **User Authentication**: Secure login and signup using **Passport.js**.
- **Expense and Investment Tracker**: Users can add, update, and view their expenses and investments in real-time.
- **Interactive Dashboard**: Displays live data in **Chart.js** graphs to give users insights into their financial habits.
- **Real-Time Data Updates**: The dashboard updates live as users add or modify their data, providing an up-to-date view of their finances.
- **MongoDB Storage**: All data is stored securely in **MongoDB**, ensuring scalability and easy management of large datasets.

---

<<<<<<< HEAD
This **Tracker App** combines powerful technologies like **GraphQL**, **MongoDB**, and **Chart.js** to provide users with a comprehensive financial tracking experience. Users can easily track their expenses and investments, view real-time data visualizations, and manage their financial data securely through an intuitive and interactive platform.
=======
This **Tracker App** combines powerful technologies like **GraphQL**, **MongoDB**, and **Chart.js** to provide users with a comprehensive financial tracking experience. Users can easily track their expenses and investments, view real-time data visualizations, and manage their financial data securely through an intuitive and interactive platform.
>>>>>>> d35540ddbb01f06963a11c7e70d2400237a77a78
