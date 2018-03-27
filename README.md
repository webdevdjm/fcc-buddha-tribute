Free Code Camp Tribute Page - Buddha
---

Build System

- Sass (LibSass)
- Autoprefixer
- CSS Minification
- JSHint
- Scss Lint (based on [this](https://github.com/causes/scss-lint/blob/master/config/default.yml) config)
- HTML Minification
- BrowserSync
- Image Minification
- GH-Pages deployment from dist/ folder

## Project Details

[Direct Link to Site](https://webdevdjm.github.io/fcc-buddha-tribute/)

### About

Project is part of the [FreeCodeCamp](https://www.freecodecamp.org) front-end certificate program.

[Link to the Project](https://www.freecodecamp.org/challenges/build-a-tribute-page)

As noted on the site itself, this was a learning project for implementing HTML and CSS. All content was copied and pasted from a [BBC Article](http://www.bbc.co.uk/timelines/zg8c9j6#z8stpv4). I take no credit for any of the content. 
I also took the opportunity to learn [Materialize CSS](http://materializecss.com). 
Much of the timeline code was derived from [this Uplabs Article](https://www.uplabs.com/posts/responsive-materialize-timeline)

### Building

1. Install node and make sure npm (Node Package Manager) is also [installed](http://blog.nodeknockout.com/post/65463770933/how-to-install-node-js-and-npm)
2. Clone this repo with `git clone https://github.com/webdevdjm/fcc-buddha-tribute.git` (in terminal) or download the zip
3. In terminal, `cd` (change directory) to the folder containing your project. (i.e. if I start at ~ and I have a Dev folder on my Desktop containing this project, I might type `cd Desktop/Dev/fcc-buddha-tribute`). Alternatively, you can type `cd ` and drag the location of the folder into your terminal and hit enter.
4. When inside the directory which contains this project in terminal, type `npm install`.
5. In the terminal, enter `gulp`
6. Take note of the Access URLs provided in your terminal. Your web page should pop up at `http://localhost:3000`. You can access this same page on your various devices in the same wifi network with the provided External URL. You can share the External URL with coworkers and they'll see whats on your screen.
7. Edit your Sass code inside of the scss folder. You can make subfolders inside of that to better organize your code. Prefix your sass files with an underscore. More info on using @import to organize your files [here](http://sass-guidelin.es/#main-file)
8. Your minified files will be automagically created and updated in `dist/`. It will create your optimized css, html, and javascript files for you. Never edit files within the `dist/` folder. (Dist stands for Distribution)
9. Keep gulp running while you're making changes. When you want to close out of the gulp task, in the terminal, hit `ctrl + C`

### Deploying to gh-pages

You can run `gulp deploy` to push your site onto the gh-pages branch. Then, you can navigate to it via *http://< your-github-username >.github.io/< project-name >* **Note:** this doesn't work if your project name is *< your-github-username  >.github.io*.