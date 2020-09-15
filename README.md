# stylus-example
A simple "holy grail" layout website to demonstrate some basic features of Stylus

I made this to provide an example to go along with a simple presentation of the [Stylus](https://stylus-lang.com/) CSS preprocessor.

## installation
Just clone the repo and run `npm i`.

## running
Once you've installed the repo, run `npm run css` inside it, and Stylus will build from `css/style.styl` to `dist/style.css` and watch the files for changes.

To view the results you'll want to open `dist/index.html`. Just opening it from your filesystem should work, but I like to use the [HTTP Server / HTML Preview](https://marketplace.visualstudio.com/items?itemName=Flixs.vs-code-http-server-and-html-preview) extension with Visual Studio Code.

## skins
You can try out skins by requiring a different file at the top of `css/style.styl`. If you want to make your own skin, copy the default skin (`css/skins/default.styl`) and change the parameters to your liking. Obviously there are many improvements that could be added, but I wanted to demonstrate how you could generate different styles in a fairly straightforward manner.

## useful links
- [Stylus Documentation](https://stylus-lang.com/)
- [Ten modern layouts in one line of CSS](https://web.dev/one-line-layouts/)
- [MDN CSS Documentation](https://developer.mozilla.org/en-US/docs/Web/CSS)
