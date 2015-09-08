# jspm-tut

A trivial repo showing how to install and use bootstrap with jspm.

Either clone this repo and then do `npm install`, `jspm install`

Or, to create it from scratch, do:

1. `npm install -g jspm` // if you haven't already
2. `mkdir jspm-tut`
3. `cd jspm-tut`
4. `npm init` // hit ENTER on all questions
5. `npm install jspm`
6. `jspm init` // again, hit ENTER on all questions
7. `jspm install bootstrap`
8. `jspm install css`
9. Create your `index.html` and `main.js` as shown/desired

You can use any server you like, but `live-server` is really cool, as it has live reload:

9. `npm install -g live-server`
10. `live-server --port=8001` // in the root directory of your project

This last command will open your default browser and serve your `index.html`.
