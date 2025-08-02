# TextToolBox

A React-based text utility application that provides various text manipulation features including word counting, character counting, case conversion, and text formatting.

## Features

- **Word Counter**: Count the number of words in your text
- **Character Counter**: Count characters in your text
- **Case Conversion**: Convert text to uppercase or lowercase
- **Text Formatting**: Remove extra spaces from text
- **Copy to Clipboard**: Copy manipulated text to clipboard
- **Dark/Light Mode**: Toggle between dark and light themes
- **Reading Time**: Estimate reading time for your text

## Technologies Used

- React 18
- React Router v6
- Bootstrap 5
- Create React App

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd text-tool-box
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### Building for Production

```bash
npm run build
```

## Deployment on Vercel

This project is configured for easy deployment on Vercel:

1. **Connect to Vercel**: 
   - Install Vercel CLI: `npm i -g vercel`
   - Run `vercel` in the project directory
   - Follow the prompts to connect your GitHub repository

2. **Automatic Deployment**:
   - Push to your main branch
   - Vercel will automatically build and deploy your app

3. **Manual Deployment**:
   ```bash
   vercel --prod
   ```

### Vercel Configuration

The project includes a `vercel.json` file that handles:
- SPA routing (all routes redirect to index.html)
- Build configuration for Create React App
- Proper output directory setup

## Project Structure

```
text-tool-box/
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── components/
│   │   ├── Navbar.js
│   │   ├── TextForm.js
│   │   ├── About.js
│   │   └── Alert.js
│   ├── App.js
│   ├── App.css
│   └── index.js
├── package.json
├── vercel.json
└── README.md
```

## Available Scripts

- `npm start`: Runs the app in development mode
- `npm test`: Launches the test runner
- `npm run build`: Builds the app for production
- `npm run eject`: Ejects from Create React App (not recommended)

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).
