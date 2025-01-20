# spotifyApp

1.Initial commit
*********************
2.Setup React project:

    Open terminal and type: npm create vite@latest
    Choose project name
    Select a framework: React
    Select a variant: Javascript
    Type in terminal:
        npm install
        npm run dev
        
    Open src folder and delete App.css file, delete content from index.css and App.jsx
*********************
3.Add content to assets folder
*************************
4.Set up Tailwind CSS:

    Install Tailwind CSS:
        npm install -D tailwindcss postcss autoprefixer
        npx tailwindcss init -p
        
    Configure your template paths inside the tailwind.config.js file:
    https://tailwindcss.com/docs/guides/vite
    
    Add the Tailwind directives to your CSS:
        @tailwind base;
        @tailwind components;
        @tailwind utilities;
        
    Start your build process:
        npm run dev
        
************************
5.Create the sidebar
********************
6.Create the player
*******************
7.Create the display
*******************
8.Create the displayHome
************************
9.Create navbar
*********************
10.Create an AlbumItem
*******************
11.Map album data using AlbumItem
******************
12.Hide scroll bar
**********************
13.Map songs data using SongItem
*********************
14.Display album data
********************
15.Redirect to home page
*****************
16.Add arrow-left and arrow-right logic
**********************
17.Display different background colors for albums
*************************
18.Create play and pause functionality
*************************
19.Show/hide play/pause icon
*************************
20.Use track state from PlayerContext to render track information
*************************
21.Add time logic
**********************
22.Add green bar logic
**********************
23.Play song based on song's id
*********************
24.Add previous and next logic
**********************
25.Create seekbar functionality
*****************************