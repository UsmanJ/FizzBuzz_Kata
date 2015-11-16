FizzBuzz Kata   [![Coverage Status](https://coveralls.io/repos/UsmanJ/FizzBuzz_Kata/badge.svg?branch=master&service=github)](https://coveralls.io/github/UsmanJ/FizzBuzz_Kata?branch=master)  [![Build Status](https://travis-ci.org/UsmanJ/FizzBuzz_Kata.svg?branch=master)](https://travis-ci.org/UsmanJ/FizzBuzz_Kata)
======================

Synopsis
---------

The task set was build a FizzBuzz program that prints the numbers from 1 to 100. For multiples of three the program prints "Fizz" instead of the number and for the multiples of five it prints "Buzz". Last but not least, for the numbers which are multiples of both three and five; the program prints "FizzBuzz".


Approach towards solving the challenge
--------------------------------------

The program was split into various user stories. These are listed below:

1) Print all numbers from 1 to 100 individually.

2) Print "Fizz" instead of the number for all the multiples of three.

3) Print "Buzz" instead of the number for all multiples of  five.

4) Print "FizzBuzz" instead of the number for numbers that are divisible by fifteen.


FizzBuzz Kata in Terminal
---------------------------------
```
irb(main):001:0> require './lib/fizzbuzz.rb'
=> true
irb(main):002:0> fizzbuzz(2)
=> 2
irb(main):003:0> fizzbuzz(18)
=> "Fizz"
irb(main):004:0> fizzbuzz(50)
=> "Buzz"
irb(main):005:0> fizzbuzz(60)
=> "FizzBuzz"
irb(main):006:0> fizzbuzz(90)
=> "FizzBuzz"
irb(main):007:0> fizzbuzz(9)
=> "Fizz"
irb(main):008:0> fizzbuzz(20)
=> "Buzz"
```
