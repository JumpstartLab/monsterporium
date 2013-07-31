# Frank's Monsterporium

Frank's Monsterporium has the best selection, nay, the ONLY selection of Frank's awesome creations on the web.

### Original Source

This project was created for the [gSchool StoreEngine Project](http://tutorials.jumpstartlab.com/projects/store_engine.html).

The original source for this codebase can be found at [github.com/raphweiner/store_engine](https://github.com/raphweiner/store_engine).

### A version of the site is up on:

http://franks-monsterporium.herokuapp.com

Log in as admin:

* email: demoXX+steve@jumpstartlab.com
* password: password

Log in as a regular user:

* email: demoXX+jeff@jumpstartlab.com
* password: password

### Setup

Clone the repo, then run:

```plain
$ bundle install
$ bundle exec rake db:create db:migrate db:seed
```

You can then run ```unicorn``` to view the site [locally on port 8080](http://localhost:8080).
