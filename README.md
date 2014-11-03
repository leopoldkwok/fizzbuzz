Fizzbuzz
===========

Fizz buzz is a group word game for children to teach them about division. Players take turns to count incrementally, replacing any number divisible by three with the word "fizz", any number divisible by five with the word "buzz" and any number that is a multiple of both 3 and 5 with the word "fizzbuzz".

The challenge was to create Fizzbuzz using Ruby in under five minutes using TDD.


Learnings
---------
* Pair programming
* Learning Test-Driven Development (TDD)
 

Technologies used
------------------

* Ruby
* Rspec
* Git

How to use
-----------

Clone the repository:

```shell
git clone git@github.com:leopoldkwok/fizzbuzz.git
```


How to run the tests:

```ruby
cd fizzbuzz
rspec
```

load irb:
```shell
irb
```

Require the files:
```ruby
require "./lib/fizzbuzz"

```

How to play:
```ruby
fizzbuzz(3)
"Fizzbuzz"

fizzbuzz(5)
"Buzz"

fizzbuzz(15)
"FizzBuzz"
```

```
