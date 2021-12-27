### BUILDING A BLOG USING MERN - Frontend
https://github.com/gurnitha/mern-blog-front

#### 1. Create a react app and modified the file structure

       > npx create-react-app my-blog

        modified:   README.md
        deleted:    src/App.test.js


#### 2. Install packages

       > npm install tailwindcss
       > npm install autoprefixer -D
       > npm install npm-run-all -D
       > npm install postcss-cli -D

        modified:   README.md
        new file:   package-lock.json
        modified:   package.json


#### 3. Modifying package.json file

        modified:   README.md
        modified:   package.json


#### 4. Delete index.css and Create styles folder and index.css file

        modified:   README.md
        deleted:    src/index.css
        modified:   src/index.js
        new file:   src/styles/index.css


#### 5. Create postcss.config.js file to Loding css

        modified:   README.md
        modified:   package-lock.json
        modified:   package.json
        modified:   src/index.js
        new file:   src/postcss.config.js
        new file:   src/styles/tailwind.css
        new file:   tailwind.config.js

        > npx tailwindcss-cli@latest init


#### 6. Create Github repository and pust the files to it

        https://github.com/gurnitha/mern-blog-front

        λ git remote add origin git@github.com:gurnitha/mern-blog-front.git

        E:\workspace\MERN\blog\my-blog (master)
        λ git branch -M main

        E:\workspace\MERN\blog\my-blog (main)
        λ git push -u origin main
        Enter passphrase for key '/c/Users/hp/.ssh/id_rsa':

        modified:   README.md