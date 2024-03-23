# LtiAdvantage

## Installation

Install the gem and add to the application's Gemfile by executing:

    $ bundle add lti_advantage

If bundler is not being used to manage dependencies, install the gem by executing:

    $ gem install lti_advantage

## Usage

This gem is a wrapper for four other gems, each of which will implement a different LTI specification, the whole of which should make implementing an LTI Advantage Complete application easy. Those four gems are:

[lti_core](https://github.com/afstanton/lti_core)
[lti_dl](https://github.com/afstanton/lti_dl)
[lti_nrps](https://github.com/afstanton/lti_nrps)
[lti_ags](https://github.com/afstanton/lti_ags)

Pointers to relevant specs will be found in each of those gems.

For those of you using Rails, you'll want to use [lti_advantage_rails](https://github.com/afstanton/lti_advantage_rails). The intent of that is to be a drop-in Rails engine to make building a LTI Advantage Complete application dead simple.

The need for this project stems from the [ims-lti](https://github.com/instructure/ims-lti) gem. While that is a decent starting point, it does not appear to implement the latest standards. This is a fresh implementation which will allow developers to use some or all relevant standards as needed.

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and the created tag, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/afstanton/lti_advantage.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
