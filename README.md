# 💎 Diamond Smile Dental Clinic

A modern, elegant, and fully responsive multi-page web application designed for **Diamond Smile Dental Clinic**. Built with semantic HTML5, modern vanilla CSS3 with glassmorphism and custom properties, and vanilla JavaScript (ES6+), the platform delivers a fast, trustworthy, and premium healthcare digital experience for patients and dental specialists.

---

## 📖 About the Project

**Diamond Smile Dental Clinic** is a premier dental practice dedicated to providing compassionate, pain-free, and advanced oral healthcare for women, children, and families. Led by Dr. Anupriya (Founder & Lead Dentist with 20+ years of clinical excellence) alongside a multidisciplinary team of 9 dental surgeons and specialists, Diamond Smile blends state-of-the-art dental technology with a warm, patient-first environment.

This web platform provides patients with an interactive digital portal:
- Instant online appointment booking with real-time status management.
- Dynamic theme switching between sophisticated Dark Mode and clean Light Mode.
- Specialist doctor directory and comprehensive 15+ treatment service catalog.
- Interactive patient portal with personal profiles, medical history records, and digital OPG X-ray reports.
- Comprehensive contact section featuring **Primary** and **Alternative** contact channels (hotline, 24/7 emergency helpline, WhatsApp, branch locations, and dedicated department emails).

---

## ✨ Features & Highlights

### 🏥 Modern Healthcare Experience
- **Fluid Hero Showcase:** Eye-catching hero section with floating clinic status pill, live patient counter badge, and clear calls to action.
- **Dark & Light Mode Support:** Ambient theme toggle with persistent user preference stored in `localStorage`.
- **Glassmorphic UI Design:** Modern translucent frosted-glass cards, smooth gradient accents, and refined micro-interactions.
- **Ambient Animated Canvas:** Soft floating ambient background blobs creating a soothing aesthetic.

### 🦷 Comprehensive Treatment Catalog
- **15+ Specialized Dental Services:**
  - LASER Gum Care & Guided Scaling
  - Tooth Fillings & Composite Restorations
  - Gentle Tooth Extractions & Wisdom Tooth Removal
  - Precision Dental Implants & Biocompatible Titanium Posts
  - Complete & Fixed Partial Dentures (Crowns & Bridges)
  - Pain-Free Root Canal Therapy (Endodontics)
  - Cosmetic Dentistry: Porcelain Veneers & Laser Teeth Whitening
  - Orthodontics: Metal/Ceramic Braces & Clear Aligners
  - Pediatric Dental Care & Habit Counseling
  - Periodontal Flap Surgery
- **Treatment Category Filter:** Interactive pills to filter services by General, Cosmetic, Surgical, and Orthodontic categories.
- **Transparent Pricing Estimates:** Up-front price starting ranges displayed for all procedures.

### 📅 Appointment Booking System
- **Online Booking Form:** Select doctor, preferred treatment, date, and morning/afternoon/evening time slot.
- **Local Persistence:** Booked appointments persist in `localStorage` across page reloads.
- **My Bookings Dashboard:** View confirmed appointments, cancel/reschedule bookings, and track appointment IDs.
- **Dynamic Notification Counter:** Red alert counter in the header showing active upcoming appointments.

### 🔐 Patient & Specialist Authentication
- **Split-Screen Interactive Modal:** Elegant login and registration modal with visual photography side and active role indicators.
- **Role-Based Demo Access:**
  - **Patient Demo:** Auto-fills credentials for test patient (`jane@example.com` / `password123`).
  - **Doctor Demo:** Auto-fills credentials for lead specialist (`dr.anupriya@diamondsmile.com` / `doctor123`).
- **Personalized Header & Profile Menu:** Shows patient avatar, full name, role badge, and fast logout actions.

### 📋 Patient Dashboard & Medical Records
- **Personal Information:** View and edit personal particulars, emergency contacts, blood group, and address.
- **Medical History Tab:** Recorded allergies, health conditions (BP, diabetic profile), and past dental treatments.
- **Digital Reports & X-Rays:** Fast access to full mouth OPG X-rays, care plans, and verifiable prescriptions.

### 📞 Contact & Alternative Reach Channels
- Complete directory of primary and alternative contact points for routine and emergency assistance.
- Interactive contact form with client-side validation.
- Responsive Google Maps embed with satellite clinic guidance.

---

## 📞 Contact Details & Alternative Channels

Diamond Smile provides multiple channels to ensure patients can easily connect for consultations, routine visits, and emergency care:

| Channel | Primary Details | Alternative / Emergency Details |
| :--- | :--- | :--- |
| **Phone Number** | `+91 98450 82190` / `+91 94480 34820` | **24/7 Helpline:** `+91 98450 82199` |
| **WhatsApp Support** | `+91 94480 34825` (Instant Chat) | Available 24/7 for emergency inquiries |
| **Email Address** | `info@diamondsmileclinic.in` | **Care & Appointments:** `care@diamondsmileclinic.in` |
| **Main Clinic** | 42 Diamond Heights Blvd, Anthivadi Hub, Hosur, TN 635109 | Landmark: Opposite Central Green Park |
| **Satellite Branch** | Suite 204, Diamond Medical Plaza, Central Ring Road, Hosur 635126 | Dedicated to pediatric & cosmetic consultations |
| **Operating Hours** | **Mon – Sat:** 8:30 AM – 7:30 PM | **Sunday:** 9:00 AM – 1:00 PM (Emergency care 24/7) |

---

## 📂 Project Architecture

```plaintext
Diamond-Smile/
├── index.html          # Main single-page landing with hero, about, treatments, doctors, appointments, reviews & contact
├── about.html          # Dedicated About Us page (clinic story, founder bio, vision & mission)
├── treatments.html     # Complete 15+ dental procedures catalog with pricing & filters
├── faqs.html           # Comprehensive patient FAQ portal with interactive accordion
├── contact.html        # Dedicated contact page with alternative channels, inquiry form & map
├── privacy.html        # Privacy Policy and patient data compliance (COPPA & GDPR aware)
├── style.css           # Central stylesheet (glassmorphism tokens, CSS variables, dark/light themes, animations)
├── script.js           # Core JavaScript (theme engine, appointment CRUD, auth state, profile modals, counters)
├── README.md           # Project documentation and guide
└── assets/
    └── images/         # High-resolution clinic photography, doctor headshots, facilities & treatment visuals
```

---

## 🛠️ Technology Stack

- **Markup:** HTML5 (Semantic, SEO-optimized tags, schema-friendly layout, accessible ARIA attributes)
- **Styling:** Vanilla CSS3 (Custom properties / variables, CSS Grid, Flexbox, glassmorphic backdrop-filters, custom keyframe animations)
- **Scripting:** Vanilla JavaScript (ES6+, DOM manipulation, `localStorage` state management, event delegation)
- **Typography:** Google Fonts (*Plus Jakarta Sans* & *Playfair Display*)
- **Icons:** Font Awesome 6.4 Free CDN

---

## 🚀 Getting Started

### Prerequisites
A modern web browser such as Google Chrome, Mozilla Firefox, Microsoft Edge, or Apple Safari.

### Running Locally
1. Clone or download the repository to your local machine:
   ```bash
   git clone https://github.com/Suvam18/Sakthi-Dental-Clinic-WebPage.git Diamond-Smile
   ```
2. Navigate into the project folder:
   ```bash
   cd Diamond-Smile
   ```
3. Open `index.html` in your favorite web browser:
   - On Windows: Double-click `index.html` or run:
     ```powershell
     start index.html
     ```
   - Alternatively, serve via VS Code **Live Server** extension or Python's built-in HTTP server:
     ```bash
     python -m http.server 5500
     ```
     Then open `http://localhost:5500` in your browser.

---

## 🧪 Demo Accounts for Testing

To test authenticated features (such as appointment scheduling, viewing booking badges, and opening the patient medical records portal):

1. Click the **Login** button in the header navigation or the drawer.
2. Click the **Auto-fill Patient Demo Login** button:
   - **Email / Phone:** `jane@example.com`
   - **Password:** `password123`
3. Click **Login** to access:
   - **My Bookings** dashboard with sample appointment
   - **Fix an Appointment** modal
   - Patient Profile & Medical History dropdown menu
4. Alternatively, use the doctor credentials:
   - **Email:** `dr.anupriya@diamondsmile.com`
   - **Password:** `doctor123`

---

## 📄 Pages Summary

1. **[index.html](file:///c:/Users/QBS%20Accounting/Documents/websites/Diamond-Smile/index.html):** The primary hub showcasing hero, philosophy, founder biography, treatment highlights, testimonials, clinic facilities, booking modal, and footer.
2. **[about.html](file:///c:/Users/QBS%20Accounting/Documents/websites/Diamond-Smile/about.html):** Deep dive into clinic heritage since 2004, Dr. Anupriya's 20+ years of dental leadership, mission, and vision.
3. **[treatments.html](file:///c:/Users/QBS%20Accounting/Documents/websites/Diamond-Smile/treatments.html):** Catalog of all 15 dental procedures complete with descriptions, indicators, and estimated cost tags.
4. **[faqs.html](file:///c:/Users/QBS%20Accounting/Documents/websites/Diamond-Smile/faqs.html):** Answers to common patient questions covering safety, pain management, children's dental care, and treatments.
5. **[contact.html](file:///c:/Users/QBS%20Accounting/Documents/websites/Diamond-Smile/contact.html):** Direct inquiries form, interactive Google Map, primary hotline, 24/7 emergency contact, and operating hours.
6. **[privacy.html](file:///c:/Users/QBS%20Accounting/Documents/websites/Diamond-Smile/privacy.html):** Data collection standards, patient record confidentiality, and contact information for privacy inquiries.

---

## 📄 License & Attribution

- **Project:** Diamond Smile Dental Clinic Web Application
- **Designed for:** Client & Academic Project Demonstration
- **Copyright:** &copy; 2026 Diamond Smile Dental Clinic. All Rights Reserved.