# Apple-Watch-Studio-UI-Frontend-Development

This is a React-based web application that allows users to select a watch case from three different materials: Aluminum, Stainless Steel, and Titanium. The selected case is highlighted, and an image of the respective case is displayed alongside its name.

## Features

- **Select Case**: Users can choose between three case types: Aluminum, Stainless Steel, and Titanium.
- **Image Preview**: An image of the selected case type is shown.
- **Highlight Selected Case**: The selected case is visually highlighted to indicate the current selection.

## Technologies Used

- **React.js**: For building the user interface and managing the application state. React enables dynamic rendering and an interactive user experience.
- **CSS Modules**: This project uses CSS Modules for scoped and modular styling, ensuring that the styles for each component don't interfere with each other.
- **JavaScript**: Used for functionality and event handling within the React components.
- **HTML5**: For structuring the content of the web page.
- **Node.js**: To run the development server using the `npm start` command.


## Folder Structure

apple-watch-studio/
├── public/
│   ├── images/              # Store images
│   │   ├── aluminum.jpg
│   │   ├── stainlesssteel.jpg
│   │   └── titanium.jpg
│   └── favicon.ico          # Favicon
├── src/
│   ├── components/          # Reusable UI components
│   │   ├── Header.js
│   │   ├── Footer.js
│   │   ├── CaseSelector.js
│   │   ├── SizeSelector.js
│   │   ├── BandSelector.js
│   │   ├── PriceDisplay.js
│   │   └── ProductCard.js   # New component for displaying product details
│   ├── pages/               # Next.js pages
│   │   ├── index.js         # Landing Page
│   │   ├── customize.js     # Customization workflow
│   │   └── customize-action.js  # New page for handling customization actions
│   └── styles/              # Styling
│       ├── globals.css      # Global styles
│       ├── Header.module.css
│       ├── CaseSelector.module.css
│       ├── BandSelector.module.css
│       ├── ProductCard.module.css   # New style for ProductCard component
│       ├── PriceDisplay.module.css  # New style for PriceDisplay component
│       ├── Header.module.css
│       ├── Index.module.css
│       ├── Customize.module.css
│       └── SizeSelector.module.css
├── .gitignore               # Ignore node_modules and build files
├── package.json             # Project metadata and scripts
└── README.md                # Documentation

