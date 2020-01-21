# How to start?

```
git clone https://github.com/a2ikm/middleman-blog-test.git
cd middleman-blog-test
bundle install
bundle exec middleman server
```

and open http://localhost:4567 with your browser.

# How this repo was created?

```
mkdir my-blog
cd my-blog
echo 2.6.5 > .ruby-version
gem install middleman
middleman init . --template=blog
bundle install
```

and updated config.rb.
