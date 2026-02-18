# ResumeCraftAI 🚀  
### AI-Powered ATS Resume Builder & Analyzer

ResumeCraftAI is a modern, AI-powered web application that helps job seekers create **professional, ATS-friendly resumes** in minutes. It analyzes resumes using intelligent logic, provides actionable feedback, and helps improve the chances of getting shortlisted by Applicant Tracking Systems (ATS).

---

## 🌐 Live Demo

- **Live Website:** https://resume-craft-ai-alpha.vercel.app/  
- **Custom Domain:** https://www.resumescraftai.tech/ (in progress)
- **Local Development URL:** http://localhost:8080  

---

## 📸 App Screenshots

### 🏠 Sign In / Home Page
![Sign In Page](screenshots/signin-home.png)

### 📊 Dashboard
![Dashboard](screenshots/dashboard.png)

### 🔍 Resume Analyzer
![Resume Analyzer](screenshots/resume-analyzer.png)

### 📈 Analyzer
![Analyzer](screenshots/analyzer.png)

### 🛠️ Builder
![Builder](screenshots/builder.png)

### 📝 Template
![Template](screenshots/template.png)

### 🔍 ATS Check
![ATS Check](screenshots/ats-check.png)

### 📈 ATS Results
![ATS Results](screenshots/ats-results.png)

---

## ✨ Features

### 🚀 AI-Powered Resume Analysis
- Intelligent analysis of resume content
- ATS compatibility checks
- Keyword and formatting suggestions

### 📝 Multiple Professional Templates
- 10+ modern, ATS-optimized resume templates
- Clean layouts suitable for recruiters
- Easy customization

### 🎯 ATS Optimization
- Designed to pass Applicant Tracking Systems
- Avoids common ATS parsing issues
- Optimized structure and formatting

### 📊 Resume Scoring
- Instant resume score
- Section-wise feedback
- Clear improvement recommendations

### 🔍 Resume Parser
- Upload an existing resume
- Automatically extract and analyze content
- Convert old resumes into editable versions

### 💾 Cloud Storage
- Secure authentication using Supabase
- Save and manage resumes in the cloud
- Access resumes from anywhere

---

## 🛠️ Tech Stack

### Frontend
- **React 18** with TypeScript
- **Vite** (build tool)
- **Tailwind CSS** + shadcn/ui
- **React Router DOM**
- **React Hook Form** + Zod
- **Framer Motion** (animations)
- **Recharts** (charts)
- **react-to-print** (PDF export)
- **@dnd-kit** (drag & drop)

### Backend
- **PostgreSQL** (database)
- **Supabase Edge Functions** (Deno runtime)
- **Row Level Security** (RLS)
- **File Storage** (Supabase Storage)

### AI
- **Google Gemini 2.5 Flash** (resume parsing)
- **Google Gemini 3 Flash Preview** (content generation & ATS analysis)

### Authentication
- **Email/Password** (Supabase Auth)
- **Google OAuth 2.0**
- **Password Reset** functionality

### Deployment
- **Vercel** (hosting)
- **Domain:** resumescraftai.tech (.tech TLD)

---

## 📁 Project Structure

```
ResumeCraftAI/
├── src/
│   ├── components/
│   │   ├── ui/           # shadcn/ui components
│   │   ├── resume/       # Resume-related components
│   │   └── landing/      # Landing page sections
│   ├── pages/
│   │   ├── Index.tsx     # Landing page
│   │   ├── Auth.tsx      # Authentication
│   │   ├── Dashboard.tsx # Main dashboard
│   │   ├── Builder.tsx   # Resume builder
│   │   ├── Analyzer.tsx  # Resume analyzer
│   │   ├── Pricing.tsx   # Pricing page
│   │   ├── PrivacyPolicy.tsx
│   │   └── TermsOfService.tsx
│   ├── contexts/
│   │   └── AuthContext.tsx
│   ├── hooks/
│   ├── services/
│   ├── utils/
│   └── App.tsx
├── supabase/
│   └── functions/
│       └── generate-content/  # AI generation edge function
├── public/
│   ├── favicon.svg
│   ├── robots.txt
│   └── google-site-verification.html
├── screenshots/
│   ├── signin-home.png
│   ├── dashboard.png
│   ├── resume-analyzer.png
│   ├── analyzer.png
│   ├── builder.png
│   ├── template.png
│   ├── ats-check.png
│   └── ats-results.png
├── package.json
├── tailwind.config.js
├── tsconfig.json
└── README.md
```

---

## ⚙️ Getting Started (Local Setup)

### Prerequisites
Ensure you have:
- Node.js (v18 or above)
- npm or yarn

> Recommended installation via nvm  
> https://github.com/nvm-sh/nvm

---

### 🚀 Installation Steps

```sh
# Clone the repository
git clone https://github.com/Vaishnotiwari12/ResumeCraftAI.git

# Navigate to project folder
cd ResumeCraftAI

# Install dependencies
npm install

# Start development server
npm run dev
```

The application will start with hot reloading enabled.

---

## 🚀 Deployment

### Vercel Deployment
- **Primary Hosting:** Vercel
- **Custom Domain:** resumescraftai.tech
- **Environment Variables:** Supabase configuration

> Make sure to configure **Supabase environment variables** before deployment.

---

## 🌍 Custom Domain Setup

### Domain: resumescraftai.tech (.tech TLD)
- **Registrar:** get.tech
- **DNS Provider:** Namecheap
- **Status:** Configuration in progress

### DNS Configuration
- **A Records:** Pointing to Vercel servers
- **CNAME:** www subdomain configuration
- **TXT Records:** Google Search Console verification

---

## 🔐 Authentication & Security

### Google OAuth 2.0
- **Status:** Submitted for verification
- **Scopes:** email, profile, openid
- **Consent Screen:** ResumeCraftAI branding

### Email Services
- **Password Reset:** SendGrid SMTP
- **Domain Authentication:** Configured for resumescraftai.tech

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Make changes
4. Test thoroughly
5. Submit a pull request

---

## 🚧 Future Enhancements

- AI resume tailoring for specific job descriptions
- Cover letter generator
- Resume download in PDF/DOCX
- Multi-language support
- Recruiter review mode
- Custom domain full integration

---

## 📄 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute it.

---

## 👨‍💻 Author

<center>
**Vaishno Tiwari**  
Full Stack Developer (MERN)  
Live Project: https://resume-craft-ai-alpha.vercel.app/

### Let's Connect!
- 📧 vaishnotiwari12@gmail.com
- 💼 [LinkedIn](https://linkedin.com/in/vaishnotiwari)
- 🐙 [GitHub](https://github.com/Vaishnotiwari12)
- 🐦 [Twitter](https://twitter.com/vaishnotiwari12)
</center>
