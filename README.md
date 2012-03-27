# SalesEngineSpecHarness

This is the evaluation test harness for SalesEngine. It requires your implementation of SalesEngine as a gem, then runs the evaluation specs against it.

## Installation

Git clone this project into a directory that lives at the same level as your `sales_engine` project directory.

And then execute:

    $ bundle

This will load in your `SalesEngine` implementation from your local file system. This test provides the CSV files at `./data` relative to the current directory from the perspective of the spec run.

## Usage

To test your implementation against the evaluation specs, run:

    $ bundle exec rspec

or:

    $ bundle exec rake

You should be all grean.