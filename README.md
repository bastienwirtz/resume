# Resume

Resume of Bastien wirtz, based on [@acro5piano](https://github.com/acro5piano/resume)'s nice resume build with Webpack + Pug + Postcss.

![screenshot](https://github.com/acro5piano/resume/blob/master/screenshot.en.png)

# Getting started

After checking out the repo, run:

```
yarn install
yarn start
```

open http://localhost:3000/ and you can see my resume.

# Write your resume with this template

Feel free to write your resume with this template, if you like it.

- `src/css/app.css` is for css
- `src/index.pug` is for template
- If you want to write your resume with sass, just add `sass-loader`

# Screenshot

To take a screenshot, start the local server and run

```bash
yarn start
yarn screenshot
```
This runs your Chrome headlessly and take an image.

# PDF

To get the pdf version, start the local server and run

```bash
yarn start
yarn pdf
```
