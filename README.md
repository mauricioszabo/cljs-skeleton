# cljs-skeleton - a ClojureScript Atom package example code

This code is meant only as a skeleton to generate ClojureScript packages. It is not
meant to be used.

To start compilation, run: `npm install` then `npx shadow-cljs watch package`

## Common bugs:

### Strange errors on activation (`$cljs is not defined`):

You can only develop a SINGLE ClojureScript package per time. If you have multiple
Atom packages written in ClojureScript, compile one as a release build (with
`shadow-cljs release <build-id>` for example) then develop the other normally.

![A screenshot of your package](https://f.cloud.github.com/assets/69169/2290250/c35d867a-a017-11e3-86be-cd7c5bf3ff9b.gif)
