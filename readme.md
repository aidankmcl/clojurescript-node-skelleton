To be able to connect Calva to shadow-cljs REPL run:

```bash
$ npx shadow-cljs watch app
$ node build/main.js
```

or use the npm scripts watch and start. Then in vscode run command "Calva: Connect to a Running REPL Server in the current Project"

To work with tests either `npx shadow-cljs watch test` or npm script watch-test.
