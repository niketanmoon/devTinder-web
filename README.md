# DevTinder

- Created app using vite + react

```
npm create vite@latest devTinder-web -- --template react
```

- removed unnecessary code and files
- installed tailwindcss

- installed daisyui
- Add Navbar component from daisy ui

- create a NavBar.jsx
- setting up routing install react router
  `npm i react-router`
- create BrowserRouter > Routes > Route / Body > Route children
- Create an outlet in your body component
- Create a footer

- Create a login page
- install axios
- set cookies when doing login - for this whitelist frontend url in backend.
- also set `{withCredentials:true}` in axios request
- For navigation use useNavigate from react router
- install redux toolkit `npm i @reduxjs/toolkit react-redux`
- Create a configure store
- Create reducer in store
- Provide a provider to the app
- create a user slice using createSlice and then export actions and reducer
- Add the userReducer to store
- Add a photo to the navbar
- Subscribe to the store using useSelector

- After refresh, the store should persist
- Logout
- Profile

- get the feed and add the feed to the store
- Build the user card on feed
- show toast message on save
- Build a feature to see all the connections

- Add connection requests page
- Added accept and reject logic for requests page
- Send ignore and interested connection request on feed page
- Added signup with token to backend
- Did E2E testing
