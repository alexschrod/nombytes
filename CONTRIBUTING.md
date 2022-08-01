# Contributing to NomBytes

The following is a set of guidelines for contributing to NomBytes.
**Pull requests are very welcome, and the below are guidelines, not rules.**
Use your best judgment, and feel free to propose changes to this document.

## Contribution Workflow

Follow these steps if you want to merge your changes to NomBytes:

1. Within your fork of [NomBytes](https://github.com/alexschrod/nombytes), create a branch for your contribution. Use a meaningful name.
1. Make your changes.
1. [Create a pull request](https://help.github.com/articles/creating-a-pull-request-from-a-fork/) against the master branch of the NomBytes repository.
1. Once the pull request is approved, the maintainer will merge it.

## Contribution Quality Standards

Some of the below quality and style standards will be enforced automatically by the [CI pipeline](https://github.com/alexschrod/nombytes/actions):

-   Separate each logical change into its own commit.
-   Each commit must pass all unit & code style tests.
-   Unit test coverage should increase the overall coverage of the project.
-   Integration test cases should be added for any new functionality added in your pull request.
-   All public functions should be documented using [Rust Documentation](https://doc.rust-lang.org/rust-by-example/meta/doc.html)
-   Add a descriptive message for each commit. Follow
    [commit message best practices](https://github.com/erlang/otp/wiki/writing-good-commit-messages).
-   Recommendations from `cargo clippy` should be applied.
-   All code should be formatted by `cargo fmt`.
-   Pull requests should be documented, explaining why the pull request was raised.
