Laptop
======

Laptop is a script to set up a Mac OS X or Linux laptop for Rails development.

Requirements
------------

### Mac OS X

We support:

* [10.9: Mavericks](https://itunes.apple.com/us/app/os-x-mavericks/id675248567)

Older versions may work but aren't regularly tested. Bug reports for older
versions are welcome.

### Linux

IT IS BROKEN RIGHT NOW

We support:

* [14.04: Trusty Tahr](https://wiki.ubuntu.com/TrustyTahr/ReleaseNotes),
* [12.04 LTS: Precise Pangolin](https://wiki.ubuntu.com/PrecisePangolin/ReleaseNotes),
* Debian stable (currently [wheezy](http://www.debian.org/releases/stable/)).
* Debian testing (currently [jessie](http://www.debian.org/releases/testing/)).

Install
-------

### Mac OS X

Read, then run the script:

    bash <(curl -s https://raw.githubusercontent.com/azevedo-252/laptop/master/mac) 2>&1 | tee ~/laptop.log

### Linux

IT IS BROKEN RIGHT NOW

Read, then run the script:

    bash <(wget -qO- https://raw.githubusercontent.com/thoughtbot/laptop/master/linux) 2>&1 | tee ~/laptop.log

Debugging
---------

Your last Laptop run will be saved to `~/laptop.log`. Read through it to see if
you can debug the issue yourself.

What it sets up
---------------

* [Bundler] for managing Ruby libraries
* [Exuberant Ctags] for indexing files for vim tab completion
* [Foreman] for serving Rails apps locally
* [gh] for interacting with the GitHub API
* [Heroku Config] for local `ENV` variables
* [Heroku Toolbelt] for interacting with the Heroku API
* [Homebrew] for managing operating system libraries (OS X only)
* [ImageMagick] for cropping and resizing images
* [Node.js] and [NPM], for running apps and installing JavaScript packages
* [NVM] for managing versions of Node.js
* [Parity] for development, staging, and production parity
* [Postgres] for storing relational data
* [Qt] for headless JavaScript testing via Capybara Webkit
* [Rails] gem for writing web applications
* [Rbenv] for managing versions of Ruby
* [Redis] for storing key-value data
* [Ruby Build] for installing Rubies
* [Ruby] stable for writing general-purpose code
* [The Silver Searcher] for finding things in files
* [Tmux] for saving project state and switching between projects
* [Watch] for periodically executing a program and displaying the output
* [Zsh] as your shell

[Bundler]: http://bundler.io/
[Exuberant Ctags]: http://ctags.sourceforge.net/
[Foreman]: https://github.com/ddollar/foreman
[gh]: https://github.com/jingweno/gh
[Heroku Config]: https://github.com/ddollar/heroku-config
[Heroku Toolbelt]: https://toolbelt.heroku.com/
[Homebrew]: http://brew.sh/
[ImageMagick]: http://www.imagemagick.org/
[Node.js]: http://nodejs.org/
[NPM]: https://www.npmjs.org/
[NVM]: https://github.com/creationix/nvm
[Parity]: https://github.com/croaky/parity
[Postgres]: http://www.postgresql.org/
[Qt]: http://qt-project.org/
[Rails]: http://rubyonrails.org/
[Rbenv]: https://github.com/sstephenson/rbenv
[Redis]: http://redis.io/
[Ruby Build]: https://github.com/sstephenson/ruby-build
[Ruby]: https://www.ruby-lang.org/en/
[The Silver Searcher]: https://github.com/ggreer/the_silver_searcher
[Tmux]: http://tmux.sourceforge.net/
[Watch]: http://linux.die.net/man/1/watch
[Zsh]: http://www.zsh.org/

It should take less than 15 minutes to install (depends on your machine).

Laptop can be run multiple times on the same machine safely. It will upgrade
already installed packages and install and activate a new version of ruby (if
one is available).

Credits
-------

![thoughtbot](http://thoughtbot.com/assets/tm/logo.png)

Laptop is maintained and funded by [thoughtbot, inc](http://thoughtbot.com/community).
The names and logos for thoughtbot are trademarks of thoughtbot, inc.

Thank you, [contributors](https://github.com/azevedo-252/laptop/graphs/contributors)!

Contributing
------------

Please see [CONTRIBUTING.md](https://github.com/azevedo-252/laptop/blob/master/CONTRIBUTING.md).

License
-------

