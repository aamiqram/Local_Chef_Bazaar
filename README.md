# LocalChefBazaar 🍳

## 🌐 Live Demo
**[Visit LocalChefBazaar →](https://local-chef-bazar.netlify.app)**

---

## 📝 Project Overview

LocalChefBazaar is a comprehensive full-stack MERN marketplace platform that bridges the gap between talented home cooks and customers seeking fresh, authentic, homemade meals. The platform enables customers to explore daily menus, place orders, leave reviews, and track their orders in real-time while supporting local culinary talent in their community.

Home chefs can showcase their cooking skills, upload custom menus with images, manage incoming orders, and generate income from their passion. Platform administrators maintain complete oversight with tools to manage users, approve chef applications, and monitor marketplace statistics.

Built with cutting-edge technologies, LocalChefBazaar delivers exceptional performance, robust security, and an intuitive user experience across all devices.

---

## ⚡ Core Features

### 🎨 Public Features
- **Animated Hero Section:** Engaging landing experience with Framer Motion animations
- **Advanced Meal Browsing:** Search functionality with price sorting (ascending/descending) and pagination (10 meals per page)
- **Detailed Meal Pages:** Comprehensive meal information including customer reviews, ratings, and favorite marking
- **Secure Authentication:** Firebase-powered login and registration with profile image upload support
- **Theme Customization:** Dark/Light mode toggle with persistent user preferences
- **Responsive Design:** Mobile-first approach ensuring seamless experience on all devices

### 👤 Customer Features
- **Order Placement:** Select meal quantities with automatic total price calculation
- **Order History:** Track all past and current orders with real-time status updates
- **Review Management:** Add, edit, and delete meal reviews with rating system
- **Favorites Collection:** Save and manage favorite meals for quick access

### 👨‍🍳 Chef Features
- **Meal Management:** Create, update, and delete meal listings with image uploads
- **Order Dashboard:** View and manage incoming orders with status controls
- **Order Processing:** Accept, cancel, or mark orders as delivered
- **Real-time Updates:** Instant notification system for new orders

### 🛡️ Admin Features
- **User Management:** Monitor all platform users with fraud detection tools
- **Role Approval System:** Review and approve chef and admin role requests
- **Automatic ID Generation:** Unique Chef IDs assigned upon approval
- **Analytics Dashboard:** Comprehensive statistics visualization using Recharts
- **Platform Moderation:** Block fraudulent users from creating meals or placing orders

### 🔒 Security & Technical Highlights
- **Dual Authentication:** Firebase Authentication combined with JWT token system
- **Secure Cookies:** httpOnly cookie implementation for enhanced security
- **Protected Routes:** Role-based access control for sensitive pages
- **Axios Interceptors:** Automatic token attachment and refresh handling
- **Form Validation:** react-hook-form integration across all input forms
- **Dynamic SEO:** Page-specific titles for improved search visibility
- **Efficient Data Fetching:** TanStack Query for optimized API calls and caching
- **User Feedback:** SweetAlert2 for elegant confirmations and notifications

---

## 🛠 Technologies Used

### Frontend Stack
![React](https://img.shields.io/badge/React_18-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router_v6-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![DaisyUI](https://img.shields.io/badge/DaisyUI-5A0EF8?style=for-the-badge&logo=daisyui&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

**Key Frontend Libraries:**
- **React 18** - Modern UI library with hooks
- **Vite** - Lightning-fast build tool and dev server
- **React Router v6** - Client-side routing and navigation
- **Tailwind CSS** - Utility-first CSS framework
- **DaisyUI** - Tailwind component library
- **Framer Motion** - Advanced animation library
- **Firebase Auth** - User authentication system
- **TanStack React Query** - Server state management
- **React Hook Form** - Form validation and handling
- **Axios** - HTTP client with interceptors
- **SweetAlert2** - Beautiful popup modals
- **Recharts** - Data visualization charts
- **React Icons** - Icon library
- **JWT Decode** - Token parsing utility

### Backend Stack
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

**Key Backend Technologies:**
- **Node.js** - JavaScript runtime environment
- **Express.js** - Minimal web application framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **Firebase Admin SDK** - Server-side Firebase integration
- **JSON Web Token** - Secure token generation and verification
- **CORS** - Cross-origin resource sharing
- **Cookie Parser** - Cookie handling middleware

---

## 📦 Dependencies

### Client-side Dependencies
```json
{
  "react": "^18.2.0",
  "react-dom": "^18.2.0",
  "react-router-dom": "^6.20.0",
  "firebase": "^10.7.1",
  "tailwindcss": "^3.4.0",
  "daisyui": "^4.4.0",
  "framer-motion": "^10.16.0",
  "@tanstack/react-query": "^5.12.0",
  "react-hook-form": "^7.48.0",
  "axios": "^1.6.2",
  "sweetalert2": "^11.10.0",
  "recharts": "^2.10.0",
  "react-icons": "^4.12.0",
  "jwt-decode": "^4.0.0"
}
```

### Server-side Dependencies
```json
{
  "express": "^4.18.2",
  "mongodb": "^6.3.0",
  "mongoose": "^8.0.3",
  "cors": "^2.8.5",
  "cookie-parser": "^1.4.6",
  "jsonwebtoken": "^9.0.2",
  "firebase-admin": "^12.0.0",
  "dotenv": "^16.3.1"
}
```

---

## 🚀 How to Run Locally

### Prerequisites
Before you begin, ensure you have the following installed:
- **Node.js** (v18 or higher)
- **npm** or **yarn** package manager
- **MongoDB** (local installation or MongoDB Atlas account)
- **Firebase Project** (for authentication)

### Installation Steps

#### 1. Clone the Repository
```bash
git clone https://github.com/aamiqram/Local_Chef_Bazaar.git
cd Local_Chef_Bazaar
```

#### 2. Setup Client (Frontend)
```bash
cd client
npm install
```

Create a `.env` file in the client directory:
```env
VITE_APIKEY=your_firebase_api_key
VITE_AUTHDOMAIN=your_firebase_auth_domain
VITE_PROJECTID=your_firebase_project_id
VITE_STORAGEBUCKET=your_firebase_storage_bucket
VITE_MESSAGINGSENDERID=your_firebase_messaging_sender_id
VITE_APPID=your_firebase_app_id
VITE_API_URL=http://localhost:5000
```

#### 3. Setup Server (Backend)
```bash
cd ../server
npm install
```

Create a `.env` file in the server directory:
```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
FIREBASE_TYPE=service_account
FIREBASE_PROJECT_ID=your_firebase_project_id
FIREBASE_PRIVATE_KEY_ID=your_private_key_id
FIREBASE_PRIVATE_KEY="your_private_key"
FIREBASE_CLIENT_EMAIL=your_client_email
FIREBASE_CLIENT_ID=your_client_id
FIREBASE_AUTH_URI=https://accounts.google.com/o/oauth2/auth
FIREBASE_TOKEN_URI=https://oauth2.googleapis.com/token
FIREBASE_AUTH_PROVIDER_CERT_URL=https://www.googleapis.com/oauth2/v1/certs
FIREBASE_CLIENT_CERT_URL=your_client_cert_url
```

#### 4. Start Development Servers

**Terminal 1 - Start Backend:**
```bash
cd server
npm run dev
```

**Terminal 2 - Start Frontend:**
```bash
cd client
npm run dev
```

#### 5. Access the Application
Open your browser and navigate to:
```
http://localhost:5173
```

The backend API will be running on:
```
http://localhost:5000
```

---

## 🔗 Related Links

- **Live Website:** [local-chef-bazar.netlify.app](https://local-chef-bazar.netlify.app)
- **GitHub Repository:** [github.com/aamiqram/Local_Chef_Bazaar](https://github.com/aamiqram/Local_Chef_Bazaar)
- **API Documentation:** Contact for API docs
- **Firebase Console:** [console.firebase.google.com](https://console.firebase.google.com)

---

## 👨‍💻 Author

**Abu Abdullah Mohammed Iqram**
- **GitHub:** [@aamiqram](https://github.com/aamiqram)
- **LinkedIn:** [aamiqram](https://www.linkedin.com/in/aamiqram/)
- **Email:** aamiqram.dev@gmail.com
- **Portfolio:** [portfolio-aami.vercel.app](https://portfolio-aami.vercel.app)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙏 Acknowledgments

- Firebase for authentication services
- MongoDB for database solutions
- Tailwind CSS and DaisyUI for UI components
- Framer Motion for smooth animations
- The open-source community for amazing packages

---

**⭐ If you like this project, please give it a star on GitHub!**
