## Start REACT project with Typescript and SCSS

- npx create-react-app my-app --template typescript
- npm install node-sass
- Convert your .css files to .scss and fix the imports

## Deploy to github pages

- npm i gh-pages
- And homepage in the package.json file
```
	...
	"private": true,
	"homepage": "https://a14narriaga.github.io/expense-tracker",
  "dependencies": {
	...
```
- Add deploy in scripts
```
	...
	"deploy": "npm run build && gh-pages -d build",
	...
```