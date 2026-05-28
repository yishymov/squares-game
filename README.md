# Squares Game

Interactive React + TypeScript game where users select a game mode and hover over generated squares on a dynamic board.

The project was built as a frontend challenge focused on API data fetching, dynamic rendering, state management and user interaction.

## Live Demo

<img width="2481" height="469" alt="image" src="https://github.com/user-attachments/assets/7463b574-38b1-416f-8a6b-445fd071c46c" />



[Open Demo](https://storied-cannoli-e29ba1.netlify.app/)

## Overview

Squares Game allows the user to choose a mode, start the game and interact with a generated grid of squares.
When the user hovers over a square, it changes state and appears in the hover history list.

The game modes are loaded from an external API, which makes the board size dynamic instead of hardcoded.

## Features

* Dynamic game modes loaded from API
* Board generation based on selected mode
* Interactive square hover behavior
* Hover history list
* State management with React hooks
* Responsive UI layout
* TypeScript-based implementation
* Vite development setup

## Tech Stack

* React
* TypeScript
* Vite
* Bootstrap
* CSS
* REST API

## Project Structure

```txt
src/
├── components/       # UI components
├── api/              # API requests
├── types/            # TypeScript types
├── App.tsx           # Main app component
└── main.tsx          # App entry point
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yishymov/squares-game.git
cd squares-game
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm run dev
```

The app will be available at:

```txt
http://localhost:5173
```

## Available Scripts

```bash
npm run dev       # Start development server
npm run build     # Build production version
npm run preview   # Preview production build
npm run lint      # Run ESLint
```

## What I Practiced

* Working with React and TypeScript
* Fetching data from an external API
* Rendering UI dynamically based on API response
* Managing component state with hooks
* Handling user interaction
* Building a small interactive frontend application
* Structuring a Vite project

## Possible Improvements

* Add loading and error states
* Improve mobile layout
* Add tests for game logic
* Add animations for square interactions
* Improve accessibility for keyboard users
* Refactor game logic into custom hooks

## Contact

**Yevhen Ishymov**
Frontend Engineer
Email: [yevhen.ishymov@gmail.com](mailto:yevhen.ishymov@gmail.com)
GitHub: [github.com/yishymov](https://github.com/yishymov)
