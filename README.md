# TailWind-Resouces

### SETUP TailWind CSS
  ✔ npm init 
   ✔ npm install -D tailwindcss postcss autoprefixer vite                         // vite is live server You can see changes instantly
    ✔ npx tailwindcss init
    
                 ( tailwind.config.js  )                                             // here content : ["*"]  is Using for accessing tailwind css to all files   
            /** @type {import('tailwindcss').Config} */
        module.exports = {
          content: ["*"],                            
          theme: {
            extend: {},
          },
          plugins: [],
        }

    
