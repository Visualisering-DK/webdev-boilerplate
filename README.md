# :bento: Webdev Boilerplate
A boilerplate for simple webdev using PostCSS, Babel and BrowserSync via npm scripts


## Intructions

1. Clone repository
2. Install development dependencies:
```bash
npm install
```
3. Start developing with live server:
```bash
npm run dev
```
4. Ready to distribute:
```bash
npm run dist
```


## Folder structure

This template assumes you're using the following structure
```bash
./dist                            # Distributable code
./src                             # Development folder
├── css/                          # Stylesheets
    ├── style.css                 # Main stylesheet
├── js                            # JavaScript
    ├── script.js                 # Main JavaScript file
├── images/                       # Images
index.html                        # Frontpage
package.json                      # All dependencies and config for the template
.gitignore             
```


## Dependencies used in this boilerplate
* [postcss](https://postcss.org/) - Tool for transforming CSS with JavaScript
* [postcss-preset-env](https://preset-env.cssdb.org/) - Tomorrow's CSS today
* [autoprefixer](https://www.npmjs.com/package/autoprefixer) - Add vendor prefixes
