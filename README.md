Document Summary Assistant:

Project Overview
An intelligent document summarization web application that analyzes and summarizes documents with precision and clarity.
Technologies Used
This project is built with modern web technologies:

Vite - Next generation frontend tooling
TypeScript - Type-safe JavaScript
React - UI component library
shadcn-ui - Beautiful, accessible components
Tailwind CSS - Utility-first CSS framework

Getting Started
Prerequisites

Node.js & npm installed - install with nvm

Installation & Development
sh# Clone the repository
git clone <YOUR_GIT_URL>

# Navigate to the project directory
cd <YOUR_PROJECT_NAME>

# Install dependencies
npm i

# Start the development server
npm run dev
The application will be available at http://localhost:5173 (or another port if 5173 is in use).
Development Workflow
Local Development
Edit files in your preferred IDE. The development server supports hot module replacement for instant updates.
GitHub Integration
Direct File Editing:

Navigate to the desired file in GitHub
Click the "Edit" button (pencil icon)
Make changes and commit directly

GitHub Codespaces:

Click the "Code" button on the repository page
Select the "Codespaces" tab
Launch a new Codespace for a cloud-based development environment

Deployment
Build for Production
shnpm run build
```
This creates an optimized production build in the `dist` directory.

### Deployment Options
Deploy to any static hosting service:
- **Vercel** - Zero-config deployment with GitHub integration
- **Netlify** - Continuous deployment from Git
- **GitHub Pages** - Free hosting for public repositories
- **AWS S3 + CloudFront** - Scalable cloud hosting
- **Custom Server** - Deploy to your own infrastructure

### Build Configuration
- **Build Command**: `npm run build`
- **Output Directory**: `dist`
- **Node Version**: 18+ recommended

## Custom Domain

To use a custom domain:
1. Deploy your application to your chosen hosting platform
2. Access your hosting provider's domain settings
3. Add your custom domain
4. Update your DNS records (A record or CNAME) as instructed by your provider
5. Enable HTTPS/SSL for secure connections

## Project Structure
```
├── src/
│   ├── components/     # React components
│   ├── pages/         # Page components
│   ├── lib/           # Utility functions
│   └── styles/        # Global styles
├── public/            # Static assets
└── dist/              # Production build (generated)
Scripts

npm run dev - Start development server
npm run build - Build for production
npm run preview - Preview production build locally
npm run lint - Run ESLint

Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
License
MIT License - feel free to use this project for personal or commercial purposes.

Built with ❤️ using modern web technologies
