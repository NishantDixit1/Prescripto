
# *Doctor Appointment System* 

A **web-based platform** for managing doctor appointments efficiently, featuring **secure authentication, real-time notifications, and an intuitive scheduling system** for up to **500 users**.  

## **Features**  
✅ **Secure Authentication** – Uses **JWT** for user authentication and role-based access control.  
✅ **Real-time Notifications** – Instant alerts for appointment confirmations, rescheduling, and cancellations.  
✅ **Scalable Backend** – Built with **Node.js, Express.js, and MongoDB**, supporting **50+ API endpoints**.  
✅ **Database Integration** – Stores **10,000+ patient and doctor records** using **SQL Server** and MongoDB.  
✅ **Responsive UI** – Developed using **React.js, Redux, and Bootstrap**, optimized for **5+ device types**.  
✅ **Cross-Browser Compatibility** – Ensures a seamless experience across different browsers.  

## **Tech Stack**  
- **Frontend:** React.js, Redux, Bootstrap  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB, SQL Server  
- **Authentication:** JWT (JSON Web Token)  
- **Notifications:** Real-time alerts for users  

## **Installation & Setup**  

### **1. Clone the Repository**  
```bash
git clone https://github.com/yourusername/doctor-appointment-system.git
cd doctor-appointment-system
```

### **2. Install Dependencies**  
```bash
npm install
```

### **3. Set Up Environment Variables**  
Create a `.env` file in the root directory and configure:  
```
MONGO_URI=your_mongodb_connection_string
SQL_SERVER_URI=your_sql_server_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

### **4. Start the Backend Server**  
```bash
npm run server
```

### **5. Start the Frontend**  
```bash
npm start
```

### **6. Access the Application**  
Open your browser and go to **http://localhost:3000/**  

## **API Endpoints**  
| Method | Endpoint           | Description |
|--------|-------------------|-------------|
| POST   | `/api/auth/login` | User login  |
| POST   | `/api/auth/register` | User registration |
| GET    | `/api/doctors` | Fetch all doctors |
| POST   | `/api/appointments/book` | Book an appointment |
| GET    | `/api/appointments/:id` | Get appointment details |

## **Contributing**  
Contributions are welcome! Feel free to fork the repository and submit a pull request.  

## **License**  
This project is licensed under the **MIT License**.  

---

Let me know if you need any modifications! 🚀
