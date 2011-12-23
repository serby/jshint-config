# My current jshint config
Here is the jshint config that I add to most projects.

## Adding to your dot files

     git clone git://github.com/serby/jshint-config ~/jshint-config
     ln -s ~/jshint-config/jshint-config.json ~/.jshintrc

## Adding to your project

If you want to get this into your project you can do the following

     mkdir support
     curl https://github.com/serby/jshit-config/raw/master/jshint-config.json > support/jshint-config.json
     git add support/jshint-config.json
     git commit -m 'Adding jshint-config.json from github.com/serby/jshint-config' support/jshint-config.json
