# Next Gen Learners Society

A gamified coding education platform for children aged 8-15 in Nepal, designed to make programming fun and accessible through interactive learning experiences.

## Mission

To nurture the next generation of tech enthusiasts by providing engaging, game-like coding education that prepares young Nepali students for future careers in technology.

## Platform Features

**Interactive Learning Environment**
- Minecraft-inspired worlds where each coding level represents a unique environment
- Collectibles system with blocks, gems, and energy points for progress tracking
- Avatar progression and customization options
- Build challenges for applying learned skills in creative projects

**Curriculum Structure**
- Level 1: Scratch Programming (visual coding fundamentals)
- Level 2: Python Basics (introduction to text-based programming)
- Level 3: Web Development (HTML, CSS, JavaScript basics)

**AI-Powered Support**
- ChatGPT integration for 24/7 coding assistance
- Child-safe responses with educational focus
- Hint system that guides without revealing solutions

**Gamification System**
- Experience points for achievements and progress
- Dynamic leveling with meaningful rewards
- Achievement badges and learning streaks
- Age-appropriate leaderboards with privacy controls

## Development Status

**Current Phase: Core Development**
- 14 active development issues covering comprehensive platform features
- Django backend architecture established
- PostgreSQL database schema designed
- User authentication system with parental controls in progress

**Upcoming**
- Frontend development (TypeScript/React)
- Game mechanics implementation
- Mobile application
- Beta testing with local schools

## Technology Stack

**Backend**
- Django with Django REST Framework
- PostgreSQL database with Redis caching
- JWT authentication with OAuth2 integration
- OpenAI GPT-4 API integration

**Frontend**
- TypeScript/React with Tailwind CSS
- Phaser.js for game elements
- WebSocket connections for real-time features

**Infrastructure**
- Docker containerization
- GitHub Actions for CI/CD
- Comprehensive logging and monitoring

## Team

| Member | Role | GitHub |
|--------|------|--------|
| Chandan Shakya | Project Lead & Backend Developer | [@ChandanShakya](https://github.com/ChandanShakya) |
| Arun Bhandari | Backend Developer | [@bhandariarun](https://github.com/bhandariarun) |
| Bibek | Backend Developer | [@Bibek99](https://github.com/Bibek99) |
| Rajesh Sir | Cybersecurity & Testing Lead | - |
| Popsicle Dai | UI/UX Design & Branding | - |

## Repositories

- **[backend](https://github.com/Next-gen-learners-society/backend)** - Django API server
- **[Frontend](https://github.com/Next-gen-learners-society/Frontend)** - React application
- **[game](https://github.com/Next-gen-learners-society/game)** - Game mechanics and interactions

## Getting Started

```bash
# Clone the backend repository
git clone https://github.com/Next-gen-learners-society/backend.git
cd backend

# Set up Python environment
python -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Configure environment
cp .env.example .env

# Run migrations
python manage.py migrate

# Start development server
python manage.py runserver
```

## Child Safety & Privacy

The platform prioritizes child safety with COPPA compliance, parental controls, content moderation, data minimization, and secure infrastructure with end-to-end encryption.

## Contributing

We welcome contributions from developers, educators, and designers passionate about coding education. Please review our issues, fork the relevant repository, create a feature branch, and submit a pull request with detailed descriptions.

## License

This project is licensed under the MIT License.