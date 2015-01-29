#Select2 4.0.0-beta.3 for rails asset pipeline

[Select2](https://github.com/select2/select2) is a jQuery based replacement for select boxes. It supports searching, remote data sets, and infinite scrolling of results.

## Usage

### Install select2-rails gem

Add `select2-rails` to your Gemfile and run `bundle install`:

	gem "select2-rails", github: 'CUnknown/select2-rails'

### Include select2-rails javascript assets

Add the following to your `app/assets/javascripts/application.js`:

	//= require select2

### Include select2-rails stylesheet assets

Add to your `app/assets/stylesheets/application.css`:

	*= require select2

## Internationalization (i18n)

The `select2-rails` now supports multiple languages.

Add the following to your `app/assets/javascripts/application.js`:

	//= require select2/"language"

## License

Selec2-Rails is released under the [MIT License](http://www.opensource.org/licenses/MIT).
