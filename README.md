# Dev Tools

Boring to add commons development gems to our projects Gemfile we decide to
create this repo to include just it to have our favourite development tools
ready to use, the tool presents in this repo are:

* [**Pry**][pry] for a powerful shell alternative to IRB.
* [**Pry Rails**][pry-rails] for additional commands (`show-routes`,
  `show-models`, `show-middleware`) in the Rails console.
* [**Pry ByeBug**][pry-byebug] to turn the console into a simple debugger.
* [**Awesome Print**][awesome_print] for stylish pretty print.
* [**Pry Doc**][pry-doc] to browse Ruby source, including C, directly from the
  console.
* [**Better Errors**][better_errors] for better Rails error page.
* [**Letter Opener**][letter_opener] for preview email in the browser.
* [**Dotenv**][dotenv-rails] to load environment variables from .env into ENV in
  development.
* [**Invoker**][invoker] for managing processes in development environment.
* [**Pulsar**][pulsar] the easy Capistrano deploy and configuration manager.
* [**Rubocop**][rubocop] for static code analyzer.

It also [configure Letter Opener][letter_opener_conf] in development environment.

## Usage

Add to your project Gemfile:

```ruby
group :development, :test do
  gem 'dev_tools', github: 'nebulab/dev_tools'
end
```

And then execute:

```
  $ bundle
```

## Contributing

1. Fork it ( https://github.com/nebulab/dev_tools/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

[pry]:                http://pry.github.com
[awesome_print]:      https://github.com/michaeldv/awesome_print
[pry-rails]:          https://github.com/rweng/pry-rails
[pry-doc]:            https://github.com/pry/pry-doc
[pry-byebug]:         https://github.com/deivid-rodriguez/pry-byebug
[better_errors]:      https://github.com/charliesome/better_errors
[letter_opener]:      https://github.com/ryanb/letter_opener
[dotenv-rails]:       https://github.com/bkeepers/dotenv
[invoker]:            https://github.com/code-mancers/invoker
[pulsar]:             https://github.com/nebulab/pulsar
[rubocop]:            https://github.com/bbatsov/rubocop
[letter_opener_conf]: https://github.com/nebulab/dev_tools/blob/master/lib/dev_tools/railtie.rb#L20
