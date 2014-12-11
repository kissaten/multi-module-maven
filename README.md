# Multi Module Maven Project Example

To deploy the standalone project run:

    $ mvn -pl standalone heroku:deploy

To deploy the war file app run:

    $ mvn -pl warfile heroku:deploy-war

Of course, this won't work unless you change the `heroku.appName` values for
each submodule.
