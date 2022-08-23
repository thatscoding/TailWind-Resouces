# TailWind-Resouces

### SETUP TailWind CSS
  ✔ npm init -y
   ✔ npm install -D tailwindcss postcss autoprefixer vite                         // vite is live server You can see changes instantly
    ✔ npx tailwindcss init -p
    
              ❤   ( tailwind.config.js  )   // here content : ["*"]  is Using for accessing tailwind css to all files   
                                   
                              /** @type {import('tailwindcss').Config} */
                          module.exports = {
                            content: ["*"],                            
                            theme: {
                              extend: {},
                            },
                            plugins: [],
                          }

❤  ADD script in package.json file
  "scripts": {
    "start": "vite"
  },
  
  ❤ Create A CSS file e.i.  ->   ( tailwind.css )  & and ADD these 3 piece of code ..
            @tailwind base;
            @tailwind components;
            @tailwind utilities;
      
   
  ✔ npm start


