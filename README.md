## Phone Catalog

A responsive and fully functional product catalog built with React and Redux Toolkit. The app includes product listings, detailed pages, a shopping cart, and a favorites page. Note: This is a clean repo. Full history of changes is available [here](https://github.com/s1rserg/react_phone-catalog).

### Live Demo

You can try the live version of the catalog [here](https://s1rserg.github.io/phone-catalog/).

### Mockup

The design was based on one of the provided UI kits. You can view the design reference [here](https://www.figma.com/design/BUusqCIMAWALqfBahnyIiH/Phone-catalog--V2--Original-Dark?node-id=0-1&p=f).

### Technologies Used

* React with TypeScript
* Redux Toolkit for global state management
* React Router for page navigation
* SCSS Modules for styling
* Vite as the development and build tool
* LocalStorage API for state persistence

### Features

* Sticky header with navigation, favorites, and cart icons
* Home page with dynamic banners, hot deals, and latest products
* Category pages for phones, tablets, and accessories
* Product sorting and pagination with URL synchronization
* Product details page with selectable options and suggested items
* Add/remove products to cart or favorites with persistent state
* Cart page with quantity controls and total price calculation
* Favorites page showing saved items
* Smooth scrolling, hover effects, and responsive layout
* Not found page for unknown routes
* Error handling and loading states

### Folder Structure
* src/api — functions for fetching product data
* src/hooks — custom hooks including typed versions of useSelector and useDispatch
* src/modules — separate folders for each page (home, cart, product, etc.) and shared components
* src/store — Redux Toolkit store and slices
* src/styles — global SCSS files (colors, variables, mixins, etc.)
* src/types — TypeScript types and interfaces
* src/utils — utility functions

### Installation
Clone this repository, run npm i and npm start and the landing page will open in your browser.
