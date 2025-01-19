# Insurance-Policy-Tracker

**Insurance-Policy-Tracker** is a web application that helps users efficiently manage their insurance policies. This tool allows users to track policies, set renewal reminders, and visualize policy details, ensuring they never miss important updates.

---

## **Features**

- **Policy Management:**
  - Add, update, and delete policies (health, life, vehicle, etc.).
  - Store essential details such as policy number, premium amount, start/end dates, and insurer information.

- **Automated Renewal Reminders:**
  - Sends email/SMS alerts for upcoming policy renewals.
  - Configurable scheduling for reminders.

- **Dashboard Insights:**
  - Visualize premiums and coverage through interactive charts.
  - Overview of total premiums paid and active policies.

- **User Authentication:**
  - Secure login and signup system.
  - Profile management for storing user preferences.

- **Optional Features:**
  - Upload and store digital copies of policies.
  - Recommendations for new policies based on existing ones.

---

## **Tech Stack**

### **Front-End:**
- **React.js:** For building a responsive and interactive user interface.
- **Chart.js/D3.js:** For data visualization and graphs.

### **Back-End:**
- **Spring Boot:** To handle API development and business logic.
- **Quartz Scheduler:** For managing reminder notifications.
- **Spring Security:** For user authentication and authorization.

### **Database:**
- **PostgreSQL/MySQL:** To store user and policy data.

### **APIs:**
- Email/SMS APIs (e.g., Twilio, Mailgun) for sending reminders.

---

## **Setup Instructions**

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/Insurance-Policy-Tracker.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd Insurance-Policy-Tracker
   ```

3. **Back-End Setup:**
   - Ensure Java and Maven are installed.
   - Navigate to the back-end folder and run:
     ```bash
     mvn spring-boot:run
     ```

4. **Front-End Setup:**
   - Ensure Node.js and npm are installed.
   - Navigate to the front-end folder and run:
     ```bash
     npm install
     npm start
     ```

5. **Database Setup:**
   - Create a PostgreSQL/MySQL database.
   - Configure the database credentials in the back-end `application.properties` file.

6. **Run the Application:**
   - Access the app at `http://localhost:3000`.

---

## **Usage**

1. Sign up and log in to your account.
2. Add policies with details like type, premium amount, and expiry date.
3. View the dashboard for a summary of active policies.
4. Receive renewal reminders via email or SMS.

---

## **Future Enhancements**

- Integration with third-party insurance APIs for recommendations.
- Advanced analytics for policy performance.
- Mobile app version for easier access.

---

## **Contributing**

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch.
3. Commit your changes and push them to your fork.
4. Submit a pull request.

---

## **License**

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## **Contact**

For questions or feedback, please contact [your-email@example.com].
