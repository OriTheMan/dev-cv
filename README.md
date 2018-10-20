# Developer CV Template

## What is it
A *Print Friendly* CV web app, which you can easily set up, modify and export to PDF.

## Tech Stack
- React
- SCSS

## How to Use
0) install Node.js, and run the 'npm install' command in the project root folder.
1) run the 'npm start' command in the project root folder and wait for the website to load on http://localhost:3000.
3) Change the title tag in src/index.html (this will be the default file name when you print).
4) Modify the data in public/cv.json.
5) Replace public/headshot.png with your own.
6) Add more resources to the public folder and use them in public/cv.json. (optional)
7) Change the font in the src/index.html stylesheet tag + src/index.scss body selector to something more you.
8) Print to PDF with Google Chrome.

## Output Example
[Click Here](https://github.com/EyalPerry/dev-cv/blob/master/output-example.pdf)

## Known Issues
1) public/cv.json.details.experience.items.projects is WIP - it is not rendered ATM.
2) public/cv.json.details.education.items.projects is WIP - it is not rendered ATM.
3) page needs to be manually reloaded after each change.
4) the layout does not scale well when there are too many items in the details pane. Pages other than the first are shown with an empty left pane which takes up space, instead of collapsing it to accomodate the items in the details pane.
