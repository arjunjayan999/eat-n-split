# Eat-n-Split

Eat-n-Split is a simple React-based web application designed to help you split bills with your friends. Add friends, track balances, and easily calculate who owes what after a shared expense.

## Features

- **Add Friends**: Add friends with their names and profile pictures.
- **Track Balances**: Keep track of how much you owe your friends or how much they owe you.
- **Split Bills**: Split expenses with friends and update balances accordingly.
- **Interactive UI**: A clean and responsive user interface for easy navigation.

## Tech Stack

- **React**: Frontend framework for building the user interface.
- **CSS**: Custom styles for a visually appealing design.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/eat-n-split.git
   cd eat-n-split

   ```

2. Install dependencies:

   ```bash
   npm install
   ```

### Running the App

To start the development server, run:

    ```bash
    npm start
    ```

This will open the app in your default browser at http://localhost:3000.

### Building for Production

To create a production build, run:

    ```bash
    npm run build
    ```

The optimized build will be available in the build folder.

## Folder Structure

```
    eat-n-split/
├── public/             # Static assets
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
├── src/                # Application source code
│   ├── App.js          # Main app component
│   ├── index.css       # Global styles
│   └── index.js        # Entry point
├── .gitignore          # Git ignore rules
├── [package.json](http://_vscodecontentref_/0)        # Project metadata and dependencies
└── [README.md](http://_vscodecontentref_/1)           # Project documentation
```

## How to Use

1. **Add Friends**: Click the "Add Friend" button, fill in the friend's name and profile picture URL, and click "Add."
2. **Select a Friend**: Click "Select" next to a friend's name to split a bill with them.
3. **Split a Bill**: Enter the bill amount, your share, and who is paying. Click "Split Bill" to update balances.
