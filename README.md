# DevTinder

- create a vite - React application
- remove unnecessary files and create a Hello World app
- Install Tailwind css
- Install DaisyUI
- Add a Navbar Component to App.jsx
- Create a Navbar.jsx separate component file
- Install react-router-dom@6
- Create BrowserRouter > Routes > Route =/ Body > RouteChildren
- Create an Outlet in your Body Component
- Create a Footer Component
- Create a Login Page
- Install axios
- CORS - install cors in Backend => add middleware to with configurations: origin, credentials: true
- whenever you're making API call so pass axios => {withCredentials: true}
- install react-redux + @reduxjs/toolkit - "https://redux-toolkit.js.org/tutorials/quick-start"
- configureStore => Provider => createSlice => add reducer to store
- Add redux devtools in chrome 
- Login and see whether your data is coming properly or not from the store
- NavBar should update as soon as user logs In
- Refactor our code to add constants file + create a components folder
- You should not be access other routes without login
- If token is not available, redirect the user to login page
- logout feature
- Get the feed and add the feed in the store
- Build the user card on the feed
- Edit Profile feature
- Show test message on save of the profile
- New Page: see all my connections
- New Page: see all my requests
- feature: Accept/Reject a request
- send/ignore the user from the feed
- sign up new user
- E2E Testing

    
Body 
    Navbar
    Route=/  => Feed
    Route=/login => Login
    Route=/profile => Profile
    Route=/signUp => SignUp
    Route=/Connections => Connections
    Footer




# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
