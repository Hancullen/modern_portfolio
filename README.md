## Responsive Online Portfolio

---

### This project contains the expanded version of [learning material](https://www.youtube.com/playlist?list=PLillGF-RfqbYoGoCjKoMOkVznV6aSXKzU)

1. Requirements

   - [Git version control](https://git-scm.com/)
   - [Node.js](https://nodejs.org/en/)
   - [Node-sass npm](https://github.com/sass/node-sass)
   - [Text Editor](https://code.visualstudio.com/) (recommend VS Code)

2. How to run project

   - Open terminal and clone this repository:
     `git clone https://github.com/Hancullen/modern_portfolio.git`
   - To install Node-sass inside VScode, open Terminal and run:
     `npm init`
     `npm i node-sass`
   - Change the code to work for your case
   - To deploy the code to github, open Terminal and install gh-pages:
     `npm i gh-pages`
   - Open the file package.json and change the link to your homepage where your portfolio will be hosted.
   - Check if it's already has this line in the package.json file, if not, add it inside "script":  
      `"deploy": "gh-pages -d dist"`
   - Run this command in the terminal:
     `npm run deploy`
   - Open the browser and type in the link to your homepage.
   - Alternatively, you can set up your work environment following this [tutorial](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/development_environment)

3. Demo

![2020-05-09 00-26-02](https://user-images.githubusercontent.com/26536430/81451616-8ff78100-918d-11ea-932a-9c3a7bab8d6a.gif)

4. Reference
   [How to make sliding text animation using pure css](https://codepen.io/alewinski/pen/grqgqx)
