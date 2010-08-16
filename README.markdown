## Sample App

This app has been produced running just a few commands:

    bundle install
    bundle exec jasmine init 
    bundle exec jazz_money init
    
Then modifying the spec/javascripts/support/jasmine.yml file to include the correct JS files to run with.

From there the standard jasmine testing approaches can be used

    rake jasmine
    
or
    
    rake jasmine:ci
    
Or jazz money can be used to use an env.js based test environment.

    bundle exec jazz_money run
