[ ![Codeship Status for ryhornalehach/jackal](https://app.codeship.com/projects/a9c580b0-cfd6-0135-a119-523bd0538b6a/status?branch=master)](https://app.codeship.com/projects/262268)
[![Coverage Status](https://coveralls.io/repos/github/ryhornalehach/jackal/badge.svg?branch=master)](https://coveralls.io/github/ryhornalehach/jackal?branch=master)
[![Maintainability](https://api.codeclimate.com/v1/badges/86b1388238faf3667f88/maintainability)](https://codeclimate.com/github/ryhornalehach/jackal/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/86b1388238faf3667f88/test_coverage)](https://codeclimate.com/github/ryhornalehach/jackal/test_coverage)

# Developed by: Ryhor (Greg) Nalehach
Jackal board game

# Technologies used in the app:
  1. Ruby on Rails
  2. React.js
  3. PostgreSQL database
  4. Materialize Framework
  5. Application deployed in production using Heroku
  6. Amazon Web Services (S3) with Carrierwave gem for photo uploads
  7. Devise gem for user authentication

# To start the application:
  1. Bundle install ruby gems:
    $ bundle
  2. Install nmp packages:
    $ npm install
  3. Create and migrate the database:
    $ rake db:create
    $ rake db:migrate
  4. Start the server:
    $ rails s
    $ npm start
  5. Test with Rspec:
    $ rake db:test:prepare
    $ rake
