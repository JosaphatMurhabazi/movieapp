# Movie Discovery + Trending Search Metrics 🎬🔥

A responsive **React + TypeScript movie discovery app** powered by the **TMDB API**, built with **Bun**, and refactored into a clean architecture with a dedicated **types** and **service** layer.  
Includes **Appwrite TablesDB** integration to store and display the **Top 5 Trending Searches** based on search popularity.

---

## ✨ Features

- 🔎 Search & explore movies using **TMDB API**
- ⏳ Debounced input for smoother UX (500ms)
- ⚡ Dynamic fetching based on popularity or search
- 🔥 Appwrite **metrics table** for trending search tracking
- 🧠 Fully refactored into:
  src/types/
  src/services/

- 📊 Trending search metrics stored as:
- `searchTerm`
- `movie_id`
- `count`
- `poster_url`

---

## ⚙ Setup & Run with Bun

### 1. Install dependencies
```bash
bun install
```
### 2. Start development server
```bash
bun run dev
```
### 3. Build for production
```bash
bun run build
```