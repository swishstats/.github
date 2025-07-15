# Welcome to SwishStats 🏀

Your go-to platform for real-time basketball statistics management, built for leagues that demand professional-grade performance tracking.

## 🚀 What We're Building

SwishStats is a comprehensive basketball statistics platform that brings ESPN-level analytics to every league. Whether you're running a local rec league or managing multiple competitive divisions, we've got you covered with:

- **Real-time Game Tracking** - Live statistics broadcasting with WebSocket technology
- **Advanced Analytics** - PER, True Shooting %, Usage Rate, and 20+ other metrics
- **Multi-tenant Architecture** - Manage multiple leagues, each with their own rules and configurations
- **Professional API** - GraphQL API with type-safe subscriptions for seamless integrations
- **Mobile-First Design** - Track games and view stats from anywhere

## 🛠️ Tech Stack

We believe in using the right tool for the job:

### Backend
- **Spring Boot 3.2** with **Kotlin** - Type-safe, expressive, and production-ready
- **GraphQL** (Netflix DGS) - Flexible API with real-time subscriptions
- **PostgreSQL 16+** - Rock-solid data persistence with advanced analytics
- **Redis** & **RabbitMQ** - High-performance caching and message queuing
- **Docker** & **AWS ECS** - Containerized deployments that scale

### Frontend
- **Next.js 15** - Server-side rendering for blazing-fast performance
- **TypeScript** - Type safety from API to UI
- **Tailwind CSS** - Beautiful, responsive designs
- **Socket.io** - Real-time game updates

## 👥 Our Development Culture

We're passionate about basketball and code quality, but we keep things balanced:

### What We Value
- **Testing** - We aim high with our test coverage, but we're pragmatic about it
- **Clean Code** - Readable, maintainable, and well-documented
- **Performance** - Every millisecond counts when you're tracking live games
- **Security** - JWT auth, OAuth2, and enterprise-grade protection

### Our Process
- **Git Flow** - Feature branches, code reviews, and clean history
- **CI/CD** - Automated testing and deployments
- **Flexibility** - We follow best practices but adapt when it makes sense

## 🎯 Getting Started

### For Developers

1. **Clone the repos**
   ```bash
   git clone [repo-url]
   cd swishstats
   ```

2. **Start the backend**
   ```bash
   cd api
   ./docker-services.sh start  # Spins up PostgreSQL, Redis, RabbitMQ
   ./gradlew bootRun
   ```

3. **Launch the frontend**
   ```bash
   cd webapp
   npm install
   npm run dev
   ```

4. **Explore the docs**
   - API Documentation: `api/docs/`
   - Frontend Guide: `webapp/README.md`
   - Architecture Overview: Check out our comprehensive PDF guides

## 🤝 Contributing

We're always looking for talented developers who share our passion for sports and technology!

### Ways to Contribute
- **Feature Development** - Pick an issue and dive in
- **Bug Fixes** - Help us squash those pesky bugs
- **Documentation** - Make our docs even better
- **Testing** - Help us reach our coverage goals
- **Performance** - Optimize queries, reduce latency, improve UX

### Getting Help
- **Discussions** - Join our GitHub Discussions
- **Issues** - Report bugs or request features
- **Pull Requests** - We review PRs quickly and provide constructive feedback

## 📊 Project Status

SwishStats is actively developed and used in production environments. We're constantly adding new features based on user feedback and league requirements.

### Recent Highlights
- WebSocket-based live game broadcasting
- Advanced statistics engine with 25+ calculated metrics
- Multi-league support with custom configurations
- OAuth2 integration (Google, Apple)

### What's Coming
- Mobile apps (React Native)
- AI-powered game insights
- Video highlight integration
- Referee management system

## 🏆 Why SwishStats?

- **Built by basketball lovers** - We understand the game and what leagues need
- **Production-tested** - Handling real games with real-time requirements
- **Developer-friendly** - Clean APIs, great docs, and a helpful community
- **Scalable** - From local tournaments to national leagues

## 📬 Get in Touch

- **Questions?** Open a discussion
- **Found a bug?** Create an issue
- **Want to contribute?** Check our open issues or propose something new

---

<p align="center">
  <img src="../../api/docs/images/logo.png" alt="SwishStats Logo" width="120">
  <br>
  <strong>SwishStats - Where Statistics Meet the Game</strong>
</p>