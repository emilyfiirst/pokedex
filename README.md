# 🧩 Pokedex Web

An interactive Pokédex built with **HTML**, **CSS**, and **JavaScript (PokeAPI)**.  
The project uses data from the [PokeAPI](https://pokeapi.co/) to list Pokémon with their type, name, number, and image.

---

## 🧠 Description

This project simulates a Pokédex, allowing users to view Pokémon in a paginated list.  
Data is dynamically loaded from the API, and the **“Load more..”** button displays additional results up to a defined limit.

---

## 🧩 Project Structure

```
📁 pokedex
│
├── index.html              # Main page structure
│
├── assets/
│   ├── css/
│   │   ├── global.css      # Global styles
│   │   └── pokedex.css     # Specific styles for the list
│   ├── js/
│   │   ├── pokemon-model.js  # Pokémon class
│   │   ├── poke-api.js       # API communication logic
│   │   └── main.js           # Rendering and main logic
│   └── images/
│       └── favicon.ico
│
└── README.md
```

---


---

## 🚀 Features

- 🔍 Lists Pokémon with **name, number, types, and image**.  
- ⚡ Uses **PokeAPI** to load real data.  
- 📱 Responsive layout (1 to 4 columns depending on screen size).  
- ➕ **“Load more..”** button to display more Pokémon (up to 151).  

---

## 🎨 Styling (CSS)

The layout uses **thematic colors based on Pokémon types**, for example:
- 🔥 `fire` → Orange  
- 🌱 `grass` → Green  
- 💧 `water` → Blue  
- ⚡ `electric` → Yellow  

Cards are organized using **CSS Grid**, and the design is fully **responsive**.

---

## ⚙️ How to Run

1. Download or clone the repository:
   ```bash
   git clone https://github.com/emilyfiirst/pokedex.git
   ```

2. Open the `index.html` file in any modern browser.

3. Click `Load more..` to view more Pokémon.

---

## 🧩 Technologies Used

- **HTML5**
- **CSS3 (Grid, Responsiveness)**
- **JavaScript (ES6)**
- **PokeAPI**

---

## 🧠 Lógica JavaScript

- `pokemon-model.js` → Defines the `Pokemon` class with main attributes.  
- `poke-api.js` → Handles fetching and converting API data.
- `main.js` → Controls rendering and Pokémon pagination in the interface.  

---

## 🧑‍💻 Author

Developed as an educational project to practice **API consumption** and **dynamic rendering with JavaScript**.
