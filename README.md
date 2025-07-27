# Ekatra - AI-Powered Teaching Assistant

<div align="center">
  <h1>🎓 Ekatra</h1>
  <p><strong>Your Intelligent AI Teaching Assistant</strong></p>
  <p>Streamline your teaching workflow with AI-powered tools and seamless Google Workspace integration</p>
</div>

## 🌟 Features

### 🤖 AI-Powered Tools
- **Lesson Plan Generator**: Create detailed, curriculum-aligned lesson plans
- **Quiz Generator**: Generate interactive quizzes with automatic Google Forms integration
- **Visual Content Generator**: Create engaging visual materials for lessons
- **AI Assistant (Alfred)**: Get instant help with teaching queries
- **Ask Agent**: Interactive AI chat for educational support

### 📚 Educational Management
- **Student Manager**: Track student progress and manage class rosters
- **Timetable Manager**: Organize and optimize your teaching schedule
- **Time Splitter**: Efficiently divide lesson time across activities
- **Doubt Scheduler**: Schedule and manage student doubt sessions

### 🔗 Google Workspace Integration
- **Google Classroom**: Sync courses, students, and assignments
- **Google Forms**: Automatically create and distribute quizzes
- **Google Meet**: Schedule and manage virtual classes
- **Gmail**: Send automated communications to parents and students
- **Google Drive**: Store and organize educational materials

### 🌍 Multilingual Support
- **Translation Tools**: Support for multiple languages
- **Internationalization**: UI available in multiple languages
- **Cultural Adaptation**: Content tailored for different regions

### 🎨 Modern UI/UX
- **Responsive Design**: Works seamlessly on desktop and mobile
- **Dark/Light Theme**: Customizable interface themes
- **Animated Components**: Engaging user experience with smooth animations
- **Accessibility**: Designed for all users

## 🚀 Quick Start

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- Google Cloud Platform account
- Firebase project

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd teacher_class-main/ekatra-ui
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Configure Firebase**
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
   - Enable Authentication and Firestore
   - Update `src/firebase.js` with your Firebase config

4. **Configure Google APIs**
   - Set up Google Cloud Platform project
   - Enable required APIs:
     - Google Classroom API
     - Google Forms API
     - Google Drive API
     - Gmail API
     - Google Meet API
   - Configure OAuth 2.0 credentials

5. **Set up environment variables**
   ```bash
   # Create .env file in ekatra-ui directory
   REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
   REACT_APP_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
   REACT_APP_FIREBASE_PROJECT_ID=your_firebase_project_id
   REACT_APP_GOOGLE_CLIENT_ID=your_google_client_id
   ```

6. **Start the development server**
   ```bash
   npm start
   # or
   yarn start
   ```

7. **Open your browser**
   Navigate to `http://localhost:3000`

## 🏗️ Project Structure

```
ekatra-ui/
├── public/                 # Static assets
├── src/
│   ├── components/         # Reusable UI components
│   │   ├── AnimatedCounter.js
│   │   ├── AnimatedIcon.js
│   │   ├── FloatingElements.js
│   │   ├── InteractiveCard.js
│   │   ├── LanguageSwitcher.js
│   │   ├── LoadingSkeleton.js
│   │   ├── MarkdownRenderer.js
│   │   ├── MorphingButton.js
│   │   ├── NotificationSystem.js
│   │   ├── ParticleBackground.js
│   │   ├── ThemeContext.js
│   │   └── VoiceInterface.js
│   ├── services/           # External service integrations
│   │   ├── GoogleAuthService.js
│   │   ├── GoogleClassroomService.js
│   │   ├── GoogleFormsService.js
│   │   ├── GoogleMeetService.js
│   │   ├── GmailService.js
│   │   └── VertexAIService.js
│   ├── App.js             # Main application component
│   ├── Dashboard.js       # Main dashboard interface
│   ├── firebase.js        # Firebase configuration
│   ├── gemini.js          # Google Gemini AI integration
│   └── ...                # Feature modules
├── package.json           # Dependencies and scripts
└── tailwind.config.js     # Tailwind CSS configuration
```

## 🔧 Configuration

### Firebase Setup
1. Create a new Firebase project
2. Enable Authentication (Email/Password)
3. Enable Firestore Database
4. Add your web app to the project
5. Copy configuration to `src/firebase.js`

### Google APIs Setup
1. Go to [Google Cloud Console](https://console.cloud.google.com/)
2. Create a new project or select existing
3. Enable the following APIs:
   - Google Classroom API
   - Google Forms API
   - Google Drive API
   - Gmail API
   - Google Meet API
4. Create OAuth 2.0 credentials
5. Configure authorized redirect URIs

### Environment Variables
Create a `.env` file in the `ekatra-ui` directory:

```env
REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id
REACT_APP_GOOGLE_CLIENT_ID=your_google_client_id
```

## 📱 Usage

### Getting Started
1. **Sign In**: Use your Google account to authenticate
2. **Dashboard**: Access all tools from the main dashboard
3. **Profile Setup**: Configure your teaching preferences
4. **Google Integration**: Connect your Google Workspace account

### Core Features

#### Lesson Planning
- Enter topic and grade level
- Select language preference
- Generate comprehensive lesson plans
- Export to various formats

#### Quiz Creation
- Specify topic and number of questions
- Generate multiple-choice quizzes
- Automatically create Google Forms
- Share with students instantly

#### Student Management
- Import students from Google Classroom
- Track attendance and progress
- Manage student information
- Generate reports

#### Communication
- Send automated emails to parents
- Schedule doubt sessions
- Manage class announcements
- Integrate with Gmail

## 🛠️ Development

### Available Scripts
- `npm start` - Start development server
- `npm build` - Build for production
- `npm test` - Run test suite
- `npm eject` - Eject from Create React App

### Code Style
- Follow ESLint configuration
- Use Prettier for formatting
- Follow React best practices
- Write meaningful commit messages

### Testing
```bash
npm test
npm run test:coverage
```

## 🔒 Security

- All API keys are stored securely
- OAuth 2.0 authentication for Google services
- Firebase security rules protect data
- HTTPS enforced in production



## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

- **Documentation**: [User Manual](USER_MANUAL.md)
- **Email**: kennethrebello253@gmail.com

## 🙏 Acknowledgments

- Google for providing excellent APIs
- Firebase for backend services
- React community for amazing tools
- All contributors and beta testers

---

<div align="center">
  <p>Made with ❤️ for educators worldwide</p>
  <p><strong>Ekatra</strong> - Empowering teachers with AI</p>
</div>
