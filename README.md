# Coding Challenges Dashboard

Welcome to the Coding Challenges Dashboard. This project is built with Next.js and includes various coding challenges.

## Getting Started

These instructions will help you set up and run the project on your local machine.

### Prerequisites

Ensure you have the following installed:
- Node.js (https://nodejs.org/)
- npm (Node Package Manager)

### Installation

1. Clone the repository:
   ```sh
   git clone <your-repository-url>
   ```
2. Navigate to the project directory:
   ```sh
   cd <your-repository-directory>
   ```
3. Install the dependencies:
   ```sh
   npm install
   ```

### Running the Development Server

1. Start the development server:
   ```sh
   npm run dev
   ```
2. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

### Project Structure

- **`components`**: Contains reusable React components.
- **`pages`**: Contains Next.js pages.
- **`styles`**: Contains CSS modules for styling.

### Challenges

1. **Challenge One - Calculator**
   - Navigate to:
     ```
     http://localhost:3000/Calculator
     ```

2. **Challenge Two - Navbar**
   - Navigate to:
     ```
     http://localhost:3000/Navbar
     ```

3. **Challenge Three - Two Sum II**
   - Navigate to the `pages` directory:
     ```sh
     cd pages
     ```
   - Run the following command:
     ```sh
     node question3.js
     ```

### Adding New Challenges

1. Create a new file in the `pages` directory for your challenge.
2. Add the necessary component logic and styling.
3. Update the `index.tsx` file to include a link to your new challenge.

### Dependencies

This project uses the following dependencies:
- Next.js
- React
- Font Awesome (for icons)

### Font Awesome Setup

1. Install Font Awesome packages:
   ```sh
   npm install @fortawesome/fontawesome-svg-core @fortawesome/free-solid-svg-icons @fortawesome/react-fontawesome
   ```
2. Configure Font Awesome in `pages/fontawesome.js`:
   ```js
   import { library } from '@fortawesome/fontawesome-svg-core';
   import { faSearch, faBars, faTimes } from '@fortawesome/free-solid-svg-icons';

   library.add(faSearch, faBars, faTimes);
   ```

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Acknowledgments

- Thanks to the Next.js team for creating an awesome framework.
- Thanks to Font Awesome for providing great icons.