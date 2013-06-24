# ThinReports Rails3 Example

The Simple Task Management App using ThinReports and Rails3.

[![Build Status](https://travis-ci.org/thinreports/thinreports-rails3-example.png)](https://travis-ci.org/thinreports/thinreports-rails3-example)
[![Dependency Status](https://gemnasium.com/thinreports/thinreports-rails3-example.png)](https://gemnasium.com/thinreports/thinreports-rails3-example)

## How to run this example:

Get this application source using git:

    $ git clone git://github.com/thinreports/thinreports-rails3-example.git

Or download ZIP/TAR archives from [here](https://github.com/thinreports/thinreports-rails3-example/archive/master.zip).

Then move to application directory, and bundle:

    $ cd thinreports-rails3-example/
    $ bundle install --without development

Setup database with seeds:

    $ bundle exec rake db:setup

Start application:

    $ bundle exec rails s

Go to `http://localhost:3000/tasks` in your browser.

### Requirements

* Ruby 1.9.2+, 2.0.0
* Rails 3.2+
* ThinReports 0.7.5+
* thinreports-rails 0.1.3
* Bundler

## Author

[Matsukei](http://www.matsukei.co.jp) Co.,Ltd.

* twitter: [@thinreports_org](https://twitter.com/thinreports_org)
* email: [thinreports@gmail.com](mailto:thinreports@gmail.com)

## License

Copyright (C) 2012 Matsukei Co.,Ltd. All rights reserved.
