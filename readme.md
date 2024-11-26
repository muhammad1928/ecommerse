
npm create vite@latest

create-vite@5.5.5
```bash
project name = frontend
cd frontend
npm install
npm install react-router-dom react-toastify
```

``` react-router-dom ``` we can create multiple doms using this

``` react-toastify ``` sending toast notifications

to run project type ``` npm run dev``` inside frontend folder

delete App.css file in src folder. also remove all the code in app.jsx file and type

``rafce`` and enter

delete react.svg file inside src/assets

clear the index.css code. 
after adding some products in assets.js

we will install tailwind using vite.
`npm install -D tailwindcss postcss autoprefixer`
init
`npx tailwindcss init -p`

paste this to tailwind.config.css file
```js
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

and this to index.css
```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

then create a folder called pages inside src folder to store our pages we will have in our project
also create a folder called components inside src folder to store our components.



# creating first page 
Go ahead and create a file called `Home.jsx`, `About.jsx`, `Content.jsx`, `Card.jsx`, `Product.jsx`, `Login.jsx`, `PlaceOrder.jsx`, `Orders.jsx` and `Collection.jsx` inside our `pages` folder.
go ahead and type `rafce` on all files to get the template in the files.

# set up Route
Now, we will set up our Route
go to file `main.jsx` and remove both `StrictMode` and insert `BrowserRouter` and import it from `react-router-dom`
add this on top `import {BrowserRouter} from react-router-dom` 