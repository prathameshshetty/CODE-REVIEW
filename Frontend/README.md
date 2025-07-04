# AI Code Reviewer – Frontend

This is the React frontend for the AI Code Reviewer project. It provides a code editor interface for users to submit code and view AI-generated reviews.

## Features

- **Live Code Editor:** Edit code with syntax highlighting (PrismJS).
- **One-Click Review:** Submit code for review with a single button.
- **Markdown Rendering:** AI feedback is displayed with formatting and code highlighting.
- **Responsive Design:** Modern, user-friendly layout.

## Tech Stack

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [PrismJS](https://prismjs.com/)
- [react-simple-code-editor](https://github.com/satya164/react-simple-code-editor)
- [react-markdown](https://github.com/remarkjs/react-markdown)
- [axios](https://axios-http.com/)

## Setup

1. **Install dependencies:**
   ```sh
   cd Frontend
   npm install
   ```

2. **Start the development server:**
   ```sh
   npm run dev
   ```

3. **Open in browser:**
   Visit [http://localhost:5173](http://localhost:5173) (default Vite port).

## Configuration

- The frontend expects the backend API to be running at `http://localhost:3000`.
- Update the API URL in [`src/App.jsx`](src/App.jsx) if your backend runs elsewhere.

## Scripts

- `npm run dev` – Start development server
- `npm run build` – Build for production
- `npm run preview` – Preview production build
- `npm run lint` – Run ESLint

---

## License

MIT
