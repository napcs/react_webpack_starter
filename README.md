# React and Webpack starter

I keep finding conflicting information online about how to get a React app going with Webpack. Partly because things won't stablize in the world of React. Babel has a new version which now has new dependencies, and every time I watch a video or read a blog post there's a new way.

So this repository is a starter kit for me that contains what currently seems to be "how you do things."

The only rule I'm breaking is that I'm using Browser-sync because I need to test things easily on many devices.

PRs welcome please. School me.

## What's in here

* `package.json` that has the deps.
    * Configures commands to run stuff too.
* `webpack.config.js`
    * Babel is configured with React and es2015 support.
    * browser-sync is configured to proxy to webpack-dev-server
* `src` folder which holds the ES2015 code that Webpack will compile
    * `src/index.js` is the entry point of the app.
    * `src/App.js` is the main application component.
    * `src/Note.js` is a Note component which is rendered by `App`.
* `js` folder which has the compiled output.
* `index.html` file that links to the compiled version of the code in the `js/` folder.


## Using this

1. Clone the repo.
2. run `npm install` to get all the deps
3. run `npm run dev` to start the development process, launch the dev server and Browser-sync
4. run `npm run build` to just build the bundle.

## Contributing

School me on this. I'm learning and would love some PRs. But I'm asking that along with a PR you explain *why* the fix or change or enhancement is important.

## License

None. Do whatever you want.
