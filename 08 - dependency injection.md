Take your text munger application, and separate the `println` logic and transformation logic into a separate class, and use dependency injection to "put" your classes and objects together. Moreover you may want to consider to mock out the random generator as well.

* update your test structure accordingly
* use mocks - mockito
* do not use any DI framework