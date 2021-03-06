# kafka-junit

[![Build Status](https://travis-ci.org/salesforce/kafka-junit.svg?branch=master)](https://travis-ci.org/salesforce/kafka-junit)

This library wraps Kafka Test Server and allows you to easily create and run tests against
a "real" kafka server running within your tests, no more needing to stand up an external kafka cluster!

## Using Kafka-JUnit with JUnit 4.

Please review [Kafka-JUnit4 Readme](kafka-junit4/) for instructions.

## Using Kafka-JUnit with JUnit 5.

Please review [Kafka-JUnit5 Readme](kafka-junit5/) for instructions.

## Changelog

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

[View Changelog](CHANGELOG.md)

# Contributing

Found a bug? Think you've got an awesome feature you want to add? We welcome contributions!


## Submitting a Contribution

1. Search for an existing issue. If none exists, create a new issue so that other contributors can keep track of what you are trying to add/fix and offer suggestions (or let you know if there is already an effort in progress).  Be sure to clearly state the problem you are trying to solve and an explanation of why you want to use the strategy you're proposing to solve it.
1. Fork this repository on GitHub and create a branch for your feature.
1. Clone your fork and branch to your local machine.
1. Commit changes to your branch.
1. Push your work up to GitHub.
1. Submit a pull request so that we can review your changes.

*Make sure that you rebase your branch off of master before opening a new pull request. We might also ask you to rebase it if master changes after you open your pull request.*

## Acceptance Criteria

We love contributions, but it's important that your pull request adhere to some of the standards we maintain in this repository. 

- All tests must be passing!
- All code changes require tests!
- All code changes must be consistent with our checkstyle rules.
- New configuration options should have proper annotations and README updates generated.
- Great inline comments.

# Other Notes

## Checkstyle

We use checkstyle aggressively on source and tests, our config is located under the 'script' folder and can be imported into your IDE of choice.

## License

[View License](LICENSE.txt)
 