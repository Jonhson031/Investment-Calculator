# Investment Calculator

A simple and interactive React application to calculate the growth of your investments over time.

## 🌐 Live Demo
👉 https://maksym-yaremko-investment-calculator.netlify.app/

The app allows you to:

- Input your **initial investment**, **annual investment**, **expected return**, and **duration**.
- Dynamically calculate yearly investment values, interest earned each year, total interest, and invested capital.
- View results in a **clean, responsive table** that updates as you change inputs.

---

## 🛠 Technologies Used

- **React** – Functional components and hooks (`useState`)
- **Vite** – Development server and build tool
- **JavaScript** – ES6+
- **HTML & CSS** – Basic styling and layout
- **Intl API** – For currency formatting

---

## ⚡ Features

- **Controlled Inputs** – Inputs are synced with React state for live updates
- **Derived State** – Investment results are recalculated automatically from state
- **Reusable Components** – Inputs and table results are modular for maintainability
- **Dynamic Table Rendering** – Shows investment growth year by year

---

## 📈 How It Works

1. Enter your initial investment, annual contribution, expected return (in %), and duration (years).  
2. The app calculates:

   - `Interest (year)` – Interest earned for that year  
   - `Total Interest` – Sum of interest earned so far  
   - `Investment Value` – Total value including contributions and interest  
   - `Invested Capital` – Total money invested so far  

3. Results are displayed in a table that updates instantly as you change inputs.



