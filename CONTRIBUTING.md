# Contributing to nuget-sparkpost

The following is a set of guidelines for contributing to nuget-sparkpost,
which is hosted by [Combeenation](https://github.com/Combeenation) on GitHub.
These are just guidelines, not rules, use your best judgment and feel free to
propose changes to this document in a pull request.

## Submitting Issues

* Before logging an issue, please [search existing issues](https://github.com/Combeenation/nuget-sparkpost/issues?q=is%3Aissue+is%3Aopen) first.

* You can create an issue [here](https://github.com/Combeenation/nuget-sparkpost/issues/new).  Please include the library version number and as much detail as possible in your report.

## Local Development

1. Fork this repo
1. Clone your fork
1. Write some code!
1. Please follow the pull request submission steps in the next section

## Contribution Steps

To contribute to nuget-sparkpost:

1. Create a new branch named after the issue you’ll be fixing (include the issue number as the branch name, example: Issue in GH is #8 then the branch name should be ISSUE-8))
1. Write corresponding tests and code (only what is needed to satisfy the issue and tests please)
    * Include your tests in the 'test' directory in an appropriate test file
    * Write code to satisfy the tests
1. Ensure automated tests pass
1. Submit a new Pull Request applying your feature/fix branch to the `master` branch

### Releasing

1. Update the `<Version>` value in `src/SparkPost/SparkPost.csproj`.
1. Merge the version change into the repository's default branch.
1. In GitHub, open **Actions** and run **Publish NuGet Package**.
1. The workflow builds and publishes `Combeenation.Libs.SparkPost` to GitHub Packages.
