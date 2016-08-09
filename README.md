# Just test for devise
 > 4.2 not work ,please comment out to test devise 4.2

```
# gem 'devise','~>4.2' # not work
gem 'devise','~>3.5.1' # Worked

```
```
bundle update
bundle exec rspec spec/features/user_registers_spec.rb
```