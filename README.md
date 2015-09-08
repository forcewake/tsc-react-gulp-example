# tsc-react-gulp-example
Example to compile React JSX with TypeScript

# Build

```sh
npm install
gulp bundle
```

The above task creates `dist/bundle.js`.


# Run

```sh
cd dist
npm install -g http-server
http-server -p 3000
```

And go to `localhost:3000/index.html` in your browser.