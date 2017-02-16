# ruby-cleverbot-api
A wrapper for the official Cleverbot API

# Installation
To use in your own program either

```ruby
gem install ruby-cleverbot-api
```
or include this in your gemfile:
```ruby
gem 'ruby-cleverbot-api'
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
response = cleverbot.send_message('Your message here')
```
Now you can display the Cleverbot response:
```ruby
puts response
```
