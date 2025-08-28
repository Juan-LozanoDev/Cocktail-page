# 🍸 Cocktail Page

A web application built with React that allows users to explore different cocktails using the Cocktail DB API. Users can search for drinks, view details, and navigate between different pages of the app.

## 🚀 Technologies Used

React (with Vite)

React Router (navigation between views)

React Hooks:

useState for managing local states

useEffect for side effects and API calls

useCallback to optimize functions and prevent unnecessary re-renders

useContext for global state management (cocktail state)

useRef for handling DOM references (search input)

## 📂 Project Structure
src/  
 ├── assets/       # Page logos  
 ├── components/   # Reusable components (Cocktail, CocktailsList, Navbar, Loading, etc.)  
 ├── pages/        # Main pages (Home, About, CocktailDetail, NotFound)  
 ├── services/     # React Context file  
 ├── styles/       # Global styles or CSS modules  
 ├── App.jsx       # Main component  
 └── main.jsx      # Entry point  

## 🌟 Main Features

🔎 Cocktail search: search by name or category

📜 Dynamic listing: fetch and display results from the API

🍹 Detailed view: ingredients, instructions, and cocktail images

📌 Navigation: multi-page navigation with React Router (Home, Details, About, ErrorPage)

🌓 Global state management with Context API

🎨 Responsive and modular design

⚙️ Installation & Setup

## Clone the repository:

git clone https://github.com/Juan-LozanoDev/Cocktail-react.git
cd Cocktail-page

Install dependencies:

pnpm install


Run the development server:

pnpm run dev


Open in browser:

http://localhost:5173

## 🔗 API Used

This project consumes the public API TheCocktailDB. Example endpoint:

https://www.thecocktaildb.com/api/json/v1/1/search.php?s=margarita
