# Toshi

A ruby wrapper around Coinbase's [Toshi](https://toshi.io/)

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'toshi'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install toshi

## Usage

```ruby
# Blocks

Toshi::Block.latest         # returns a Block instance
Toshi::Block.find('hash')   # returns a Block instance
Toshi::Block.find('height') # returns a Block instance
Toshi::Block.all            # returns an array of Block instances

```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/gary-rafferty/toshi.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

