# 🗺️ Plan With Akki

Plan With Akki is a React-based web application that allows users to explore and manage a curated list of travel destinations across India. Users can read more about each destination, remove destinations they are not interested in, and refresh the list to start over.

## ✨ Features

- 🏞️ **View Destinations:** Browse a list of beautiful travel destinations, each with an image, name, price, and description.
- 📖 **Read More / Show Less:** Expand or collapse the description for each destination to read more details.
- ❌ **Remove Destinations:** Remove destinations you are not interested in from the list.
- 🔄 **Refresh List:** If all destinations are removed, easily refresh the list to restore all destinations.

## 🗂️ Project Structure

```
plan-with-akki/
├── public/
│   └── index.html
├── src/
│   ├── App.js
│   ├── data.js
│   ├── index.css
│   ├── index.js
│   └── components/
│       ├── Card.js
│       └── Tours.js
├── package.json
└── .gitignore
```

- [`src/App.js`](src/App.js): Main application logic, manages state and handles removing/restoring tours.
- [`src/data.js`](src/data.js): Contains the static data for all destinations.
- [`src/components/Tours.js`](src/components/Tours.js): Renders the list of destination cards.
- [`src/components/Card.js`](src/components/Card.js): Displays individual destination details and handles "Read More" and "Remove" actions.
- [`src/index.js`](src/index.js): Entry point for the React app.
- [`src/index.css`](src/index.css): Styles for the application.

## 🚀 Getting Started

### 🛠️ Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### 📦 Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/plan-with-akki.git
   cd plan-with-akki
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

### ▶️ Running the Application

Start the development server:

```sh
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

### 🏗️ Building for Production

To create a production build:

```sh
npm run build
```

## 📝 Usage

- 🏝️ Browse the list of destinations.
- 📖 Click **Read More** to expand the description, or **Show Less** to collapse it.
- ❌ Click **Not Interested** to remove a destination from the list.
- 🔄 If all destinations are removed, click **Refresh** to restore the full list.

## 🧩 Customization

- ✏️ To add or modify destinations, edit the [`src/data.js`](src/data.js) file.
- 🎨 To update styles, modify [`src/index.css`](src/index.css).

## 📄 License

This project is for educational purposes.

---

**🌏 Enjoy planning your next trip with Plan With
