# AI Lukas 🤖

## Overview

AI Lukas is a comprehensive AI platform designed for teams to maximize their AI capabilities. Built on a modern full-stack foundation, it provides a centralized hub for AI-powered collaboration, document management, and seamless integration with various AI services.

## 🚀 Key Features

### Core AI Platform
- **AI Document Management** - Store, organize, and share AI-related documents
- **Team Collaboration** - Real-time collaboration on AI projects
- **AI Service Integration** - Connect with various AI companies and services
- **Knowledge Base** - Centralized repository for AI insights and learnings

### Technical Foundation
- **Authentication System** - Secure team member access with social login options
- **Payment Integration** - Subscription-based access to premium AI features
- **Multi-language Support** - International team collaboration
- **Responsive Design** - Works seamlessly across all devices
- **Real-time Updates** - Live collaboration and notifications

## 🛠 Tech Stack

- **Frontend**: React Router, TypeScript, Tailwind CSS
- **Backend**: Supabase (Database & Auth)
- **ORM**: Drizzle ORM
- **Email**: Resend
- **Payments**: Stripe
- **Deployment**: Vercel/Netlify ready
- **Testing**: Playwright E2E tests

## 🏗 Project Structure

```
app/
├── features/           # Feature-based modules
│   ├── auth/          # Authentication system
│   ├── users/         # User management
│   ├── payments/      # Subscription handling
│   └── blog/          # Documentation & updates
├── core/              # Core components & utilities
│   ├── components/    # Reusable UI components
│   ├── layouts/       # Page layouts
│   └── lib/          # Utility functions
└── locales/          # Internationalization
```

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- Docker (optional, for containerized development)
- Supabase account
- Stripe account (for payments)

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/sooin123456/aiproject_1.git
   cd aiproject_1
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   # Fill in your Supabase, Stripe, and other API keys
   ```

4. **Start development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:5173`

## 🔧 Development

### Available Scripts
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run test` - Run E2E tests
- `npm run db:generate` - Generate database types
- `npm run db:migrate` - Run database migrations

### Docker Development
```bash
docker-compose up -d
```

## 📋 Roadmap

### Phase 1: Core Platform ✅
- [x] User authentication & team management
- [x] Basic document storage
- [x] Payment integration
- [x] Multi-language support

### Phase 2: AI Integration 🚧
- [ ] AI document analysis
- [ ] Chat interface for AI interactions
- [ ] AI service API integrations
- [ ] Knowledge base with AI insights

### Phase 3: Advanced Features 📅
- [ ] Real-time AI collaboration
- [ ] AI model comparison tools
- [ ] Automated AI workflow creation
- [ ] Advanced analytics dashboard

## 🤝 Contributing

We welcome contributions from team members! Please read our contributing guidelines before submitting pull requests.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](./LICENSE.md) file for details.

## 📞 Support

For support and questions, please reach out to the development team or create an issue in this repository.

---

**Built with ❤️ for AI-powered teams**
