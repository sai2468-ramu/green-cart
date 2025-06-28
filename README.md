 GreenCart  
**Shop Smart: the digital grocery store**

[![Demo Video](
https://github.com/user-attachments/assets/8540a61d-dcb2-4417-8762-08d126cdf56a
)

GreenCart is a MERN + Vite-based grocery shopping platform designed to make online grocery shopping **fast**, **efficient**, and **user-friendly**. Ideal for both shoppers and sellers, it offers:

- 🛒 Product browsing, cart management, and checkout
- 🏷️ Seller dashboard for product listing, order handling
- 🔐 User and seller authentication
- ☁️ Image uploads with Cloudinary
- 🔄 File upload via Multer
- ⚡ Fast frontend via Vite
🛠️ Tech Stack
Frontend: React + Vite

Backend: Node.js with Express
Database: MongoDB
Image Uploads: Multer + Cloudinary
Auth: JWT and session-based
Deployment-ready: Configured for Vercel & cross-platform compatibility

🚀 Live Demo
Watch the 

https://github.com/user-attachments/assets/3b451225-eeaf-49b5-8b97-e388ee579082

demo video to see GreenCart in action:

Adding products to cart (classic and seller flows)

Seller dashboard for adding products & managing orders

Smooth authentication and error states

💾 Installation
Clone the repo
bash
Copy
Edit
git clone https://github.com/sai2468-ramu/green-cart.git
cd green-cart
Environment variables
Create a .env file in server/:
ini
Copy
Edit
PORT=5000
MONGO_URI=<your_mongo_connection_string>
CLOUDINARY_CLOUD_NAME=<name>
CLOUDINARY_API_KEY=<key>
CLOUDINARY_API_SECRET=<secret>
JWT_SECRET=<your_jwt_secret>

Install dependencies (both client / server):
bash
Copy
Edit
npm install        # in root (installs nothing, but safe)
cd client && npm install
cd ../server && npm install
Run locally

Frontend:
bash
Copy
Edit
cd client && npm run dev

Backend:
bash
Copy
Edit
cd server && npm run dev

Client: http://localhost:5173
Server: http://localhost:5000
KEY FEATURES:
Testing features
User signup/login
Browse products and add to cart
Seller signup/login, product listing
Order creation & management

🛡️ Features
Frontend:
Vite-fueled React app with fast HMR
Clean UI for users and sellers
SVG icons & responsive design

Backend:
RESTful API endpoints (/products, /orders, /seller, /cart, /user)
Controllers for Cart, Order, Seller, etc.
Multer for handling file uploads
Cloudinary for storing and serving images
Secure authentication (JWT), Auth middleware

📝 Folder Structure
bash
Copy
Edit
/client       # Vite + React
  ├─ src/assets      # SVG icons, images
  ├─ src/pages       # AddProduct, Orders, ProductList, SellerLayout...
/server       # Express backend
  ├─ controllers     # business logic
  ├─ models          # MongoDB schemas
  ├─ middlewares     # auth logic
  ├─ routes          # API routes
/configs/cloudinary.js, db.js, multer.js, ...
server.js, .env.example, vercel.json

🧪 Next Steps & Contributions
✅ Add more features: ratings, reviews, payments
🌐 Deploy frontend via Vercel / Netlify
💾 Deploy backend via Render / Railway
📦 Containerize with Docker
📈 Optimize performance and accessibility

Pull requests are welcome! Fork, make changes, and raise a PR. You can also open GitHub issues for bugs or feature requests.

📞 Contact
Built by PARAPATLA SAI KUMAR (sai2468-ramu)
Have questions or want to collaborate? Feel free to reach out via GitHub or [parapatlasai123@gmail.com].

✅ How to Add This to Your Repo
Create or update README.md in the root.
Paste the content above and customize fields (demo runtime, contact info).

Commit & push:

bash
Copy
Edit
git add README.md
git commit -m "Add README with project overview and instructions"
git push
