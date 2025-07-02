# FinEdu - Gamified Learning Platform for Accounting Students

## Overview
FinEdu is a web-based, gamified learning platform designed to help accounting students master financial concepts through interactive games, quizzes, and challenges. Built with HTML, CSS (using Tailwind CSS), and JavaScript, FinEdu offers a professional and vibrant user experience that is engaging and educational. The platform is fully deployable as a static website, requiring no backend for core functionality.

## Features
- **Simulated Accounting Ledger Games**: Record debit and credit transactions to balance a ledger and earn points.
- **IFRS vs GAAP Comparison Module**: An interactive quiz to learn key differences between IFRS and GAAP standards.
- **Beat the Balance Sheet Challenge**: A timed challenge to balance a balance sheet by calculating the correct equity value.
- **Gamified Progress Tracking**: Earn points, level up (Beginner, Intermediate, Expert), and collect badges based on performance.
- **Leaderboards**: A static leaderboard showcasing top players (dynamic functionality requires a backend).
- **Real-Life Business Case Simulations**: Placeholder for future simulations of financial scenarios (to be expanded).
- **Responsive Design**: A professional, vibrant UI with modals, animations, and smooth scrolling for an optimal user experience across devices.

## Getting Started

### Prerequisites
- A web browser (e.g., Chrome, Firefox, Safari).
- A web server (e.g., GitHub Pages, Netlify, or a local server like Live Server in VS Code) to host the static site.
- No backend or dependencies are required for core functionality.

### Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/muzzamil2/FinEdu.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd FinEdu
   ```
3. **Host the Website**:
   - Option 1: Use a static hosting service like GitHub Pages or Netlify by uploading the `index.html` file.
   - Option 2: Run a local server using a tool like Live Server in VS Code or Python's HTTP server:
     ```bash
     python -m http.server 8000
     ```
   - Open your browser and navigate to `http://localhost:8000`.

### File Structure
- `index.html`: The main file containing the HTML, CSS (via Tailwind CSS CDN), and JavaScript for the entire application.
- (No additional files are required, as the project is a single-page application.)

## How to Play
1. **Ledger Game**: Access from the "Games" section. Enter debit and credit amounts (e.g., $5000 for both) to balance the ledger and earn 100 points.
2. **IFRS vs GAAP Quiz**: Answer questions about IFRS and GAAP differences. Correct answers earn 50 points and advance to the next question.
3. **Beat the Balance Sheet**: Calculate the correct equity value ($4000) within 30 seconds to earn 200 points.
4. **Track Progress**: Check the "Progress" section to view your points, level, badges, and progress bar.
5. **Explore Features**: Navigate through the site to learn about all features and contact the team via the form (requires backend for functionality).

## Future Enhancements
- Add a backend (e.g., Node.js, Firebase) for dynamic leaderboards, user authentication, and form submissions.
- Expand business case simulations with realistic financial scenarios.
- Include more quiz questions and ledger game scenarios.
- Implement local storage or a database to persist user progress across sessions.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For questions or feedback, reach out via the contact form on the website or open an issue on GitHub.

---

Built with ❤️ by Muzzamil for accounting students worldwide.
