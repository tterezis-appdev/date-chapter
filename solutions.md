# Solutions

## formatted.rb

```ruby
require "date"
today = Date.today
p "The year is: #{today.year}, the calendar day is: #{today.day}, and the month is: #{today.month}."
```

## math.rb

```ruby
require "date"
days_between = Date.today - Date.new(1995, 12, 21)
days_between_to_integer = days_between.to_i
p "Ruby is #{days_between_to_integer} days old!"
```

## monday.rb

```ruby
require "date"
p "Is today Monday? #{Date.today.monday?}"
```
