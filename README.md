# RemoteRecord::GitHub

GitHub remote record classes.

## Installation

Add this to your application's Gemfile:

```ruby
gem 'remote_record'
gem 'remote_record-github'
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install remote_record remote_record-github

## Usage

Create an ActiveRecord model, then follow the [RemoteRecord](https://github.com/raisedevs/remote_record) guide to configure it to use this `RemoteRecord` class. If your model is called `GitHub::UserReference`, it'll automatically infer that it should use `RemoteRecord::GitHub::User`. Otherwise, you'll need to manually specify the `klass` when configuring your remote reference.

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/raisedevs/remote_record-github. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [code of conduct](https://github.com/raisedevs/remote_record-github/blob/master/CODE_OF_CONDUCT.md).


## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the RemoteRecord::GitHub project's codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/[USERNAME]/remote_record-github/blob/master/CODE_OF_CONDUCT.md).
