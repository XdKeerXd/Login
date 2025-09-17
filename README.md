# React Auth (localStorage)

This is a minimal React app (Vite) with Register, Login and Dashboard pages. User data is stored in localStorage for demo purposes only.

Security note: This example stores passwords in plaintext in localStorage which is NOT suitable for production. Use a proper backend and hashed passwords for real apps.

Getting started (PowerShell on Windows):

```powershell
# from the project root (where package.json lives)
npm install
npm run dev
```

Then open the local dev URL Vite prints (usually http://localhost:5173).

What is included:
- `src/auth.js` - small auth service that saves users and current user into localStorage
- `src/components/Register.jsx` - registration form
- `src/components/Login.jsx` - login form
- `src/components/Dashboard.jsx` - protected dashboard

Next steps / improvements:
- Add password hashing and server-side authentication
- Add form validation and better UX
- Add persistent sessions and tokens
