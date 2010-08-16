## Sample App

This app has been produced running just a few commands revolving around the standard ones : 

    mkdir <app>
    _add Gemfile_
    bundle install
    bundle exec jasmine init 
    bundle exec jazz_money init
    
Then modifying the spec/javascripts/support/jasmine.yml file to include the correct JS files to run with.

To trial this app, clone it and then run

    bundle install
    bundle exec jazz_money run
