# react-hello-world-example
A "Hello World" example made with React

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Welp-IT/react-hello-world-example.git
cd react-hello-world-example
```

2. Install dependencies:
```bash
npm install
```

### Running the Application

#### Development Mode
To start the development server:
```bash
npm start
```

The application will automatically open in your browser at http://localhost:3000

#### Production Build
To create a production build:
```bash
npm run build
```

The optimized files will be generated in the `dist/` directory.

## Project Structure

```
react-hello-world-example/
├── public/
│   └── index.html          # HTML template
├── src/
│   ├── App.js              # Main React component
│   └── index.js            # Application entry point
├── package.json            # Dependencies and scripts
└── webpack.config.js       # Webpack configuration
```

## Technologies Used

- React 18.2.0
- React DOM 18.2.0
- Webpack 5
- Babel
