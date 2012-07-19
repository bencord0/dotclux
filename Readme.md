# .clux
Use this if you are clux and you are reinstalling linux.

## Usage
Get git, clone the repo, then plow through these scripts:

````bash

cd && mkdir repos && cd repos
git clone https://github.com/clux/.clux.git fix
cd fix
./node 0.8.3
./git
./cpy
./repos
cd .. && rm -rf fix
````

## Script Description
### node
Gets specified version of node, makes, installs and chowns global node_modules folder.
Last two steps will ask for sudo pw.

### git
Initializes the git config and sets up ssh keys to paste to github.

### cpy
Installs settings for:

- sublime_text2
- jshint

### repos
Clones, links and installs all modules, dependencies so that everything's linked together nicely for continued development.

## License
Licensed to clux exclusively
