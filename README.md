Getting Started with Ruby & Sinatra on Heroku
=============================================

Run Locally
-----------

1. Install RVM

2. Setup RVM

    On Ubuntu:

        source ~/.rvm/scripts/rvm
        rvm requirements
        rvm install 1.9.2
        rvm use 1.9.2

3. Install the dependencies with bundle

        bundle install

4. Start the app

        bundle exec ruby web.rb

5. Test the app in your browser: http://localhost:4567


Run on Heroku
-------------

1. Create the app

        heroku create -s cedar

2. Deploy the app

        git push heroku master

3. Open the app in your browser

        heroku open

