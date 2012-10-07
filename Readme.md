# My current .jshintrc

Here is the .jshintrc that I use for all new JavaScript projects.

## Adding to your dot files (*nix)

     git clone git://github.com/serby/jshint-config ~/jshint-config
     ln -s ~/jshint-config/jshint-config.json ~/.jshintrc

## Adding to your project

Putting a copy in your project root will ensure that the project always has the same jshint config 
even if your global .jshintrc config changes. Also it allow you to put project specific predefs that
don't belone belong in your global.

     curl https://raw.github.com/serby/jshint-config/master/jshint-config.json > .jshintrc
     git add .jshintrc
     git commit -m 'Adding .jshintrc from github.com/serby/jshint-config' .jshintrc