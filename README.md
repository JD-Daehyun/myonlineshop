# Online Shopping Website

This project is an online shopping website built using React, React Router DOM, and React Redux.

## Features

### React Router DOM for Home and Cart Page
- **Home Page**: Displays products available for purchase.
- **Cart Page**: Displays products added to the cart.
- **Persistent Navbar**: Always present on the page.
- **BrowserRouter**: Wraps `App` in `index.js` to enable routing features.

### React Redux
1. **Create Store Directory**: Manages the entire state.
2. **Create Slices**: Define slices with name, initial state, and actions using `createSlice`. Export slice reducer and actions.
3. **Configure Store**: Combine all reducers using `configureStore`.
4. **useDispatch**: Allows components to dispatch actions.
5. **useSelector**: Allows components to access state.

Redux is similar to the Context API, providing global state management and helping to avoid prop drilling. However, Redux offers additional features and a more structured approach, making it more suitable for larger applications with complex state logic.

### Optional Chaining (`?.`)
- Safely access deeply nested properties without explicit null checks.

