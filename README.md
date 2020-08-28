# Social Network Theme With Sass

The code in this repository is based on [Traversy Media's](https://www.traversymedia.com/) video tutorial on building a [Social Network Theme With Sass](https://www.youtube.com/playlist?list=PLillGF-Rfqba3xeEvDzIcUCxwMlGiewfV).  The aim of the tutorial is to build reusable CSS components with [Sass](https://sass-lang.com) that can be used throughout the website.

## Prerequisites

1. Install [nodejs](https://nodejs.org/).
2. Install [Visual Studio Code](https://code.visualstudio.com/download). If you don't install it you will have to find another way of [installing sass](https://sass-lang.com/install) and compilation. The rest of the instructions assume you are using Visual Studio Code.

## Running the code

1. You will be prompted to install the the recommended extensions when you open up the code folder in Visual Studio Code. Go ahead and install these. They are `Live Sass`, `Live Server` and `Prettier`. The first is essential as it compiles `.scss` and `.sass` files into `.css` files. The last two extensions are optional. The recommended extensions can be found in the `extensions.json` file in the `.vscode` directory should you wish to edit these. Likewise in the same directory you can find the `settings.json` file should you wish to edit the recommended settings.
2. Run ```npm install``` from the project folder to install the dependencies listed in the `package.json` file.
3. Click the `Watch Sass` button in the bottom bar of Visual Studio Code to perform live comilation of SASS or SCSS to CSS.
4. Open `dist/index.html`, right click on the text editor area and select `Open With Live Server` (or run your preferred development server) to launch the application in your default web browser.
