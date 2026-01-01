# ❄️ WarmPaws — Pet Care in Winter

🔗 **Live Site:** https://stupendous-fox-6aad8d.netlify.app

---

## 📌 About the Project
**WarmPaws** is a winter-focused pet care platform that helps pet owners keep their furry friends warm, safe, and healthy during the cold season. Users can explore local pet care services, winter clothing for pets, grooming options, expert tips, and book services easily.

This project is built as a **Single Page Application (SPA)** using **React** with **Firebase Authentication**.

---

## 🚀 Main Features
- 🐾 Winter care services for pets (clothing, grooming, tips, etc.)  
- 🔐 Firebase authentication (Email/Password & Google Login)  
- 🧩 Protected routes: service details and booking accessible only after login  
- 📝 Book services through a simple form with success toast  
- 📋 My Profile page to view and update user info (Name, Image)  
- 💡 Extra homepage section with winter care tips and expert vets  
- 🌗 Responsive on mobile, tablet, and desktop  
- ✨ Subtle animations using **AOS**, **Swiper.js**, and **react-hot-toast**  

---

## 🧩 Pages Included
- Home (hero slider + services + winter tips + expert vets + extra section)  
- Services / Service Details (Protected Route)  
- My Profile (View & Update)  
- Login & Signup  
- Forgot Password  
- 404 Page (without Navbar & Footer)  

---

## 🛠️ Technologies Used
**Frontend:** React, React Router, Tailwind CSS, Firebase  
**Packages Used:** AOS, Swiper.js, react-hot-toast  
**Others:** Animate.css, React-Spring  

---

## 🧱 JSON Data
Winter care services are stored in a JSON file with fields like:  
`serviceId, serviceName, providerName, providerEmail, price, rating, slotsAvailable, description, image, category`  

Example:

```json
{
  "serviceId": 1,
  "serviceName": "Winter Coat Fitting for Dogs",
  "providerName": "PawCare Studio",
  "providerEmail": "info@pawcare.com",
  "price": 25,
  "rating": 4.9,
  "slotsAvailable": 4,
  "description": "Custom coat fitting and warm outfit options to keep your dog comfortable in the cold.",
  "image": "https://i.postimg.cc/example1.png",
  "category": "Clothing"
}
