# Store React Application

This project is a tech store website developed using React and TypeScript. It provides a single-page application (SPA) experience with optimized rendering and advanced features for managing and browsing tech products, including phones, tablets, and accessories.

##**Main Technologies Used**
1. **React**: A JavaScript library for building user interfaces. This project uses functional components for efficient and reusable UI elements.
2. **TypeScript**: A typed superset of JavaScript that compiles to plain JavaScript. It helps in catching errors early and improving code quality.
3. **react-router-dom**: A library for handling routing in React applications, enabling navigation between different views within the single-page app.

##**Hooks**: 
Various React hooks are employed for optimized state management and side effects:
1. **useMemo**: For memoizing expensive calculations.
2. **useState**: For managing component state.
3. **useRef**: For accessing and interacting with DOM elements.
4. **useEffect**: For handling side effects and data fetching.
5. **useReducer**: For managing complex state logic.
   
##**Features**

**Product Management**
1. **Product Loading**: Products are fetched from an API using fetch with async/await for asynchronous data retrieval.
2. **Context Management**: Three separate contexts manage the state of products, cart, and favorites:
   a. Product Context: Manages product-related data.
   b. Cart Context: Handles cart operations and persists data in localStorage.
   c. Favorites Context: Manages favorite items and also stores them in localStorage.
   
**User Interaction**
1. **Search**: Users can search for products by name across different categories.
2. **Sorting**: Products can be sorted based on:
     a. Alphabetical order
     2. Cheapest
     3. Newest
3. **Page Size Selection**: Users can choose how many products to display per page.
4. **Product Page**
   Product Variants:
   Users can select different colors or memory sizes for the same model directly from the product page.
   Suggested Products:
   Suggestions Logic: Suggested products are determined by filtering products based on the current category and matching capacity or color.
5. **Favorites and Cart**:
   Users can add products to their favorites or cart directly from the catalog. They can also edit the quantity of items or remove them from the cart directly within the cart interface.
6. **Responsive Design**: The application is designed to be responsive, adapting to various screen sizes, including large screens, desktops, tablets, and mobile devices.
