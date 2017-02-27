# ruby-cleverbot-api
A wrapper for the official Cleverbot API

# Installation - Release Versions
To use in your own program either

```ruby
gem install ruby-cleverbot-api
```
or to use bundler include this in your gemfile:
```ruby
gem 'ruby-cleverbot-api'
```

If you take the bundler route run after adding it to your Gemfile:
```sh
bundle
```

# Installation - Development Version
To use the latest version which could be unstable:

Add the following to your Gemfile:
```ruby
gem 'ruby-cleverbot-api',  git: 'https://github.com/FormalHellhound/ruby-cleverbot-api.git'
```

# Usage
Obtain an API key from: http://www.cleverbot.com/api/

Then require the gem in your project.
```ruby
require 'ruby-cleverbot-api'
```
Then initialize the cleverbot api wrapper
```ruby
cleverbot = Cleverbot.new('Your API key')
```
After the initialization send a message and get a response using:
```ruby
puts cleverbot.send_message('Your message here')
```
If you would like to reset your conversation string to start a fresh conversation use:
```ruby
cleverbot.reset
```
