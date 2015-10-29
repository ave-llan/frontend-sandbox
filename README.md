A simple sandbox for front-end development with a live view of your code, automatically updated whenever it is changed.

## Set up

Clone the repository, deleting .git for clean start.

```
git clone https://github.com/jrleszcz/frontend-sandbox.git frontend-sandbox
rm -rf frontend-sandbox/.git
```

Move into your new project directory and install packages.

```
cd frontend-sandbox
npm install
```

## Usage

To watch your project for changes and update them live in a simple server, open two terminal tabs run:

```
npm run watch
```

```
npm run view
```