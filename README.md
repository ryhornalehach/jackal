[ ![Codeship Status for ryhornalehach/gregnalehach](https://app.codeship.com/projects/e12ec0c0-bb54-0135-598e-7277cb23256d/status?branch=master)](https://app.codeship.com/projects/259331)

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
