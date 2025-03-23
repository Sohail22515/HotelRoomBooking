# 🏨 Hotel Booking System  

## 📌 Overview  
This is a **full-stack hotel booking system** built using **Node.js, Express, and MongoDB**. It provides a **user-friendly** interface for clients to **search for hotels and rooms**, book their stay, and ensure no double bookings occur. The **admin panel** allows complete management of hotels, rooms, and users.  

---

## 🚀 Features  

### ✨ Client Side  
- 🔍 **Search for hotels and rooms** by location, date range, and number of persons.  
- 🏨 **Book a room** (ensuring no double bookings for the same dates).  
- 📅 **Booking validation**: A room cannot be booked by another user for the same date range.  

### 🔐 Admin Side  
- 📋 **Manage bookings**: View all customer reservations.  
- 🏨 **Manage hotels & rooms**: Add, update, or delete hotels and rooms.  
- 👤 **User Management**: Create or remove users.  
- 🔒 **Secure Admin Access**: Only admins can access the admin panel.  

---

## 🛠️ Tech Stack  
- **Frontend**: React.js, Css, Scss  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  

---

## ⚙️ Installation and Setup  

1️⃣ Clone the repository:  
```bash
git clone https://github.com/yourusername/hotel-booking-system.git
cd hotel-booking-system
```
2️⃣ Install dependencies:
```bash
npm install
```

3️⃣ Set up environment variables:
Create a .env file in the root directory and add:
```bash
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=8800
```

4️⃣ Start the server:
```bash
node index.js #for api (backend)
yarn start    #for client/admin
```

## 🎯 Future Enhancements

- ✅ Payment gateway integration
- ✅ Email notifications for bookings
- ✅ Improved UI design

## 📜 License

This project is open-source. Feel free to contribute!




