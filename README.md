##RailsAdmin Bootstrap Flatly theme.

![ScreenShot](https://raw.github.com/konjoot/rails_admin_flatly_theme/master/preview.png)

### Usage

In your `Gemfile`:
```ruby
gem 'rails_admin_flatly_theme', :git => 'git://github.com/konjoot/rails_admin_flatly_theme.git', :branch => 'release_1.0'
```

Or for last changes:

```ruby
gem 'rails_admin_flatly_theme', :git => 'git://github.com/konjoot/rails_admin_flatly_theme.git'
```


Inside `config/application.rb`, just after `Bundler.require`:

```ruby
ENV['RAILS_ADMIN_THEME'] = 'flatly_theme'
```

Then run `bundle`, `rake assets:clean` and finally `rake assets:precompile`.

May be you should run `rm -rf tmp/cache/assets/development/`, for changes to take effect.



This project distributes under MIT-LICENSE.
