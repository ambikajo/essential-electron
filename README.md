# Museum Compendium

This is a informational website about museums and project management. The website is built from this [repository](https://github.com/jlord/essential-electron)

### Build it

The site is built from one markdown file `index.md` with one bit of inline HTML for creating the styles on the vocabulary words. The markdown is parsed and turned into HTML, sandwiched between `header.html` and `footer.html` through a tiny Node script in `index.js`.

The stylesheet is `style.css` and it uses system fonts unless you have Source Sans Pro installed locally.

You'll need [Node.js](https://nodejs.org) to build this site:

```bash
# Clone repository
git clone https://github.com/jlord/essential-electron.git
# Go into repository clone
cd museum-compendium
# Install dependencies
npm install
# Rebuild if changes have been made to:
# index.md, footer.html, header.html
npm start
# Open the page in your browser
open index.html
```

After you are done with your changes, build the website as per the instructions above and then git commit/push (whatever)