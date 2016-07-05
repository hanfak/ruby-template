# Ruby Project Template

A template to avoid setting up and get started on testing and creating code.

## Priors

### Install essential software

Such as Xcode, Homebrew, RVM, Ruby, pry

1. Go to ```http://www.preparetocode.io/```
2. choose operating system
3. click on xcode and follow instructions and download and install everything

## Install gems

Any other gems needed for the project, type in ```Gemfile```

and at command line type ```bundle install```

## Tests

All stored in ```spec/``` folder

Feature tests are done in ```spec/features/``` folder

Naming of tests match the naming of scripts(ie ```example.rb```) that are tested, with ```_spec``` added at the end (ie ```example_spec.rb```)

To require the file to be tested, at top of spec, type ```require <example>```

Example of how tests are setup are given in ```spec/class_name_spec```

## Scripts

Are stored in ```lib/``` folder

## Coverage

To see coverage of tests, open ```coverage/.last_run.json```

## Console

Run ```irb``` or ```pry``` (if installed) to access ruby console.

## Running tests

At command line run ```rspec``` to run all tests (or whatever name the file is called)

To run individual tests ```rspec spec/class_name_spec.rb``` (or whatever file wanted to test)

## Running scripts

At command line run ```ruby class_name.rb``` (or whatever name the file is called)
