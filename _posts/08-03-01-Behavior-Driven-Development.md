---
isChild: true
---

## Behavior Driven Development

There are two different types of Behavior-Driven Development (BDD): SpecBDD and StoryBDD. SpecBDD focuses on technical behavior or code, while StoryBDD focuses on business or feature behaviors or interactions. PHP has frameworks for both types of BDD.

With StoryBDD, you write human-readable stories that describe the behavior of your application. These stories 
can then be run as actual tests against your application. The framework used in PHP applications for StoryBDD
is Behat, which is inspired by Ruby's [Cucumber](http://cukes.info/) project and implements the Gherkin DSL
for describing feature behavior.

With SpecBDD, you write specifications that describe how your actual code should behave. Instead of testing
a function or method, you are describing how that function or method should behave. PHP offers the PHPSpec framework for this purpose. This framework is inspired
by the [RSpec project](http://rspec.info/) for Ruby.

### BDD Links    

* [Behat](http://behat.org/) is inspired by Ruby's [Cucumber](http://cukes.info/) project 
* [PHPSpec](http://www.phpspec.net/) the SpecBDD framework for PHP
* [Codeception](http://codeception.com) is designed write behavioral scenarios in PHP as from the eyes of actual tester.
