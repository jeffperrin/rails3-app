Rails 3, RSpec, Factory Girl, Haml, and jQuery
=============================================================

# Usage

Easily generate a Rails 3 application with RSpec, Factory Girl, Haml, and
jQuery in one line:

    % rails new my_app --skip-bundle -J -T -m \
    https://github.com/jeffperrin/rails3-app/raw/master/app.rb

## Need Cucumber?

Use this generator file instead:

    % rails new my_app --skip-bundle -J -T -m \
    https://github.com/jeffperrin/rails3-app/raw/master/cuke.rb

rvm
---

Generates an `.rvmrc` to specify a gemset.

Generators
----------

We use the Factory Girl and Haml Rails 3 generators &mdash; the generators for
RSpec are packaged within their respective gems. The Factory Girl and Haml generators are from the
[ haml-rails ](http://github.com/indirect/haml-rails) and
[factory_girl_generator](http://github.com/leshill/factory_girl_generator)
gems.

jQuery
-------------------

We use the jquery-rails generator to pull in the latest and greatest `jQuery` into the app.

git
---

We love `git`, so the application has a git repo initialized with all the initial changes staged.

Wrap Up
-------

After the application has been generated, there are a few final command to finish the install, check the output!
