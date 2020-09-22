
# How to create this file structure from Terminal!
## You too can create, edit and remove files using only text commands!
### Because UI is for woosies!


1) First you need to open Terminal!

1) Enter `git clone <address of repository>`
1) Enter `mkdir -p src/assets` to create your folder structure!
1) Enter `touch greeting.md` to create an empty markup file
1) Enter `cd src` to enter the "src" directory
1) Enter `touch index.html` to create an empty HTML file
1) Enter `cd assets` to reach the "assets" directory.  
    * It is good practice to keep your assets organized in their own directories

        * It reduces clutter
1) Enter `touch style.css` and `touch app.js` to create the empty "CSS" and "JavaScript" files
    * It is good practice to put code in these files to work properly
1) Enter `../..` to navigate back to the root directory
    * I'm not sure if this is good practice or not
        * I might have been channeling some old DOS code
            * I am that old
1) Enter `echo 'Hello there!' > greeting.md` to add "Hello there!" to "greeting.md"
1) Check your work using `ls -R`
    * Its good practice to always check your work
1) If your work looks right, then you can send it to GitHub!

# Sending it to Github!

1) Enter `git add -A` to add your current status to the local Git
1) Enter `git commit -m "creates the file structure"`  to let git know you are serious about your changes
1) Enter `git push origin main` to send it up into the clouds
    * i.e. Github

