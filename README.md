Heroku buildpack: anyscript
=======================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) to run a script in your repo.

Usage
-----

####Example installation:

    $ heroku buildpacks:add --index 1 http://github.com/bendytree/anyscript.git
    
####Example usage:

Add a file named `heroku-buildpack-anyscript.sh` to the root of your project that has a script like:

    #!/bin/sh
        
    echo "this is my script"


