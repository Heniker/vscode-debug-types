# Infer debug types

VSCode extension that can create type representation for runtime debug values.
Currently only works with TypeScript.
It will also try to find your alredy defined interfaces and use them instead of creating a new one.
After installing you should have `Infer type` command in command pallete during debug (it has no deafult keybinding).

### How to install

It's not published to VSCode store atm, but you can easily grab the latest [release](https://github.com/Heniker/vscode-infer-debug-types/releases) and drag'n'drop it into your vscode extensions menu.

### Does it currently even work?

Gosh, I hope it does. I mean, clearly there are still things to be done, but basic functionalty should be there (I hope). I will provide some demos and tests later, but please submit an issue if you think something is not working as you would expect it to.

### Shoutouts

Kudos to [ts-morph](https://github.com/dsherret/ts-morph) for making it feasible to work with TypeScript compiler API.
