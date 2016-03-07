
# SheetSlide.io

Create your reveal.js presentation from spreadsheet!

![Mockup disply](/mockups/mockup.png)


## Running Locally

Make sure you have Ruby installed.  Also, install the [Heroku Toolbelt](https://toolbelt.heroku.com/).

```sh
$ git clone git@github.com:heroku/ruby-getting-started.git
$ cd ruby-getting-started
$ bundle install
$ bundle exec rake db:create db:migrate
$ heroku local
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```sh
$ heroku create
$ git push heroku master
$ heroku run rake db:migrate
$ heroku open
```

or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)


## Dev notes

This is a side project for me to learn Ruby on Rails from my Django land.

Some reference that I have read through:

* http://guides.rubyonrails.org/getting_started.html
* https://devcenter.heroku.com/articles/getting-started-with-ruby  (what this repo is based on)