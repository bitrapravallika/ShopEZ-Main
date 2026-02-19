# ShopEZ-Main
A full-stack MERN web application that enables users to browse products, manage cart, place orders, and allows admins to manage products and customer orders efficiently.
🛒 ShopEZ - MERN Stack E-Commerce Application

ShopEZ is a Full-Stack E-Commerce Web Application developed using the MERN Stack (MongoDB, Express.js, React.js, Node.js) as part of the SmartBridge Project.

This application provides a smooth online shopping experience where users can browse products, add items to cart, place orders, and view order history. It also includes an Admin Panel to manage products and customer orders.

📂 Project Structure

The project consists of two main folders:

client/ → Frontend developed using React.js

server/ → Backend developed using Node.js & Express.js

⚙️ Installation Guide
1️⃣ Clone the Repository
git clone https://github.com/bitrapravallika/ShopEZ-Main.git
cd ShopEZ-Main

2️⃣ Install Dependencies

⚠️ Ignore warnings or vulnerabilities while installing.

▶️ Install Server Dependencies
cd server
npm install

▶️ Install Client Dependencies
cd client
npm install

🌐 Environment Variables Setup

Open the server/index.js file and replace MongoDB connection URL with your MongoDB Atlas URL.

mongoose.connect("mongodb+srv://username:password@cluster0.mongodb.net/ShopEZ")
.then(()=>console.log("MongoDB Connected Successfully"))
.catch((err)=>console.log(err));

▶️ Running the Application
Start Backend Server (Port: 5000)
cd server
node index.js


OR

npm run dev

Start Frontend Client (Port: 3000)
cd client
npm start


⚠️ If you encounter errors:

Delete node_modules folder and run:

npm install


Then restart the application.

✨ Features
👤 User Functionalities

✔️ User Registration & Login
✔️ Browse Products
✔️ Filter Products by:

Category

Gender

Price

Popularity

✔️ Add Products to Cart
✔️ Checkout & Place Orders
✔️ View Order History
✔️ Enter Address & Contact Details

🛠️ Admin Functionalities
🔐 Admin Login Credentials:

Email: admin@gmail.com

Password: admin

✔️ Add Products
✔️ Update Products
✔️ Delete Products
✔️ View All Orders
✔️ Update Order Status
✔️ Cancel Orders
✔️ Manage Customer Orders

🧰 Tech Stack Used
Technology	Usage
React.js	Frontend
Redux Toolkit	State Management
Node.js	Backend
Express.js	Server
MongoDB	
CSS	Styling
📄 Project Report
[
👉 http//drive.google.com/drive/folders/1-ddhqS0lPmihN1hVaAYcd0Aa0T63Ow0R?usp=drive_link

🎥 Demo Video

👉 https://drive.google.com/file/d/1DTuQjBZ-Mdas54ma5d4k4lmoVjqcCwB-/view?usp=drive_link
🔗 GitHub Repository

👉 https://github.com/bitrapravallika/ShopEZ-Main

📌 Conclusion

ShopEZ is a responsive and user-friendly application developed using MERN Stack technologies. It demonstrates complete CRUD operations, authentication, product management, and order tracking functionalities for both users and administrators.
