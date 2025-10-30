# 🌿 Prakriti Wellness Management

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![React](https://img.shields.io/badge/React-18.2.0-61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0.2-3178C6)
![Vite](https://img.shields.io/badge/Vite-4.4.5-646CFF)
![Supabase](https://img.shields.io/badge/Supabase-Latest-3ECF8E)

</div>

## 📋 Overview

**Prakriti Wellness Management** is a modern, full-stack web application that bridges traditional Ayurvedic wellness practices with cutting-edge technology. Built with React, TypeScript, and Supabase, it offers a comprehensive platform for personalized health management, integrating ancient wisdom with modern convenience.

## ✨ Key Features

### 🧑‍💼 User Features
- Smart Profile Management
  - Detailed personal health information storage
  - Secure data encryption
  - Profile progress tracking

- 📊 Prakriti Analysis
  - Scientific questionnaire for dosha assessment
  - Detailed analysis of Vata, Pitta, and Kapha
  - Interactive assessment interface
  - Comprehensive results explanation

- 🥗 Personalized Diet Charts
  - Custom meal plans based on Prakriti
  - Seasonal diet adjustments
  - Nutritional recommendations
  - Food compatibility guides

- ⏰ Daily Schedule (Dinacharya)
  - Personalized daily routines
  - Optimal timing suggestions for:
    - Wake-up and sleep schedules
    - Exercise and meditation
    - Meals and rest periods

- 📅 Follow-up System
  - Automated reminder system
  - Progress tracking
  - Interactive feedback collection
  - Wellness journey documentation

### 👨‍💼 Admin Features
- Comprehensive Dashboard
  - User analytics and insights
  - Progress monitoring
  - System performance metrics
  - Batch user management

## 🛠️ Technical Stack

- **Frontend:**
  - React 18.2.0 with TypeScript
  - Vite 4.4.5 for build tooling
  - TailwindCSS for styling
  - React Router for navigation

- **Backend:**
  - Supabase for database and authentication
  - PostgreSQL for data storage
  - RESTful API architecture

- **Security:**
  - JWT authentication
  - Role-based access control
  - Data encryption at rest

## ✅ Prerequisites

Before setup, ensure you have:

- **Node.js** (v16+) – [Download](https://nodejs.org/)
- **npm** (v7+) – Package manager
- **Git** – [Download](https://git-scm.com/)
- **Supabase Account** – [Sign Up](https://supabase.com)
- **Supabase CLI** – For database migrations

## 🚀 Getting Started

1. **Clone & Navigate**
   ```bash
   git clone https://github.com/neeraj59089/---Prakriti-Wellness-Management.git
   cd Prakriti-Wellness-Management
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Configure Supabase**
   - Create a `.env` file:
     ```bash
     VITE_SUPABASE_URL=your_supabase_project_url
     VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
     ```

4. **Setup Database**
   ```bash
   npx supabase link --project-ref your-project-id
   npx supabase migration up --linked
   ```

5. **Launch Development Server**
   ```bash
   npm run dev
   ```

## 🧪 Testing Guide

### User Testing
1. Access the platform through `/auth`
2. Complete profile setup
3. Take Prakriti assessment
4. Review diet recommendations
5. Check daily schedule
6. Monitor progress tracking

### Admin Testing
1. Login through `/admin`
2. Navigate dashboard
3. Manage user records
4. Create/monitor follow-ups
5. Generate reports

> 💡 **Pro Tip:** Use separate browser instances for simultaneous user/admin testing

## 📚 Documentation

- [User Guide](docs/user-guide.md)
- [Admin Manual](docs/admin-manual.md)
- [API Documentation](docs/api-docs.md)
- [Database Schema](docs/schema.md)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Team

- Neeraj Mishra - Lead Developer [@neeraj59089](https://github.com/neeraj59089)

## 🙏 Acknowledgments

- Ayurvedic Health Practitioners
- Open Source Community
- React Development Team
- Supabase Team

---
<div align="center">
Made with ❤️ for better health and wellness
</div>