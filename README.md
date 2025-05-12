# PrepGenie: AI-Powered Interview Preparation Platform

## 🚀 Project Overview

PrepGenie is an innovative platform that empowers job seekers to conduct AI-powered mock interviews, leveraging cutting-edge technologies to simulate real-world interview experiences and provide personalized feedback.

## 🌟 Key Features

- **AI-Powered Voice Interviews**: Conduct realistic mock interviews using VAPI's voice agent technology
- **Intelligent Feedback**: Powered by Gemini 2.0 Flash AI for comprehensive interview analysis
- **Secure Authentication**: Robust user management with Firebase Authentication
- **Performance Tracking**: Store and track interview results using Firebase Firestore

## 🛠 Tech Stack

- **Frontend**: Next.js 14
- **Language**: TypeScript
- **AI Services**:
  - VAPI (Voice AI Agent)
  - Gemini 2.0 Flash (Google AI)
- **Backend & Authentication**: Firebase
  - Firestore Database
  - Firebase Authentication
- **Styling**: Tailwind CSS
- **State Management**: React Hooks

## 📦 Prerequisites

- Node.js (v18+ recommended)
- npm or Yarn
- Firebase Account
- Gemini AI API Key
- VAPI Account

## 🔧 Installation

1. Clone the repository

```bash
git clone https://github.com/null-kaustubh/prepgenie.git
cd prepgenie
```

2. Install dependencies

```bash
npm install
# or
yarn install
```

3. Set up environment variables
   Create a `.env.local` file in the root directory with the following variables:

```env
# Firebase Configuration
NEXT_PUBLIC_FIREBASE_API_KEY=your_firebase_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_firebase_project_id

# Gemini AI Configuration
NEXT_PUBLIC_GEMINI_API_KEY=your_gemini_api_key

# VAPI Configuration
NEXT_PUBLIC_VAPI_API_KEY=your_vapi_api_key
```

4. Run the development server

```bash
npm run dev
# or
yarn dev
```

## 🌐 Deployment

Recommended platforms:

- Vercel (Optimal for Next.js)
- Netlify
- Heroku

Deployment steps:

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Set environment variables in the deployment platform

## 📝 Key Components

### Authentication

- User registration and login
- OAuth support via Firebase
- Secure route protection

### Interview Workflow

1. Select Interview Type

   - Technical Interviews
   - Behavioral Interviews
   - Role-Specific Scenarios

2. AI Voice Interview

   - Real-time voice interaction
   - Adaptive questioning
   - Natural language processing

3. Feedback Generation
   - Detailed performance analysis
   - Strengths and improvement areas
   - Suggested resources

## 🔒 Security Considerations

- Firebase Security Rules
- Input validation
- Rate limiting
- Secure API key management

## 🚧 Future Roadmap

- [ ] Multi-language support
- [ ] More interview domains
- [ ] Advanced analytics dashboard
- [ ] Machine learning-based personalized coaching
- [ ] Integration with job application platforms
- [ ] Customizable interview scenarios

## 💡 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📊 Performance Optimization

- Server-side rendering (SSR)
- Incremental Static Regeneration (ISR)
- Lazy loading of components
- Efficient state management

## 🆘 Troubleshooting

- Ensure all API keys are correctly configured
- Check Firebase project settings
- Verify VAPI and Gemini AI integrations
- Review browser console for any errors

## 🤝 Contact

Your Name - [kaustubhs2903@gmail.com]

Project Link: [https://github.com/null-kaustubh/prepgenie](https://github.com/null-kaustubh/prepgenie)

---
