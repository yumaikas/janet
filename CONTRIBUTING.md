# Guidelines for contributing to Janet

Thanks for taking time to contribute to Janet!

Please read this document before making contributions.

## Reporting bugs

* Check past and current issues to see if your problem has been run into before.
* If you can't find a past issue for your problem, or if the issues has been closed
  you should open a new issue. If there is a closed issue that is relevant, make
  sure to reference it.
* As with any project, include a comprehensive description of the problem and instructions
  on how to reproduce it. If it is a compiler or language bug, please try to include a minimal
  example. This means don't post all 200 lines of code from your project, but spend some time
  distilling the problem to just the relevant code.
* Add the `bug` tag to the issue.

## Contributing Changes

If you want to contribute some code to the project, please submit a pull request and
follow the below guidelines. Not all changes will be merged, and some pull requests
may require changes before being merged.

* Include a description of the changes.
* If there are changes to the compiler or the language, please include tests in the test folder.
  The test suites are not organized in any particular way now, so simply add your tests
  to one of the test suite files (test/suite0.janet, test/suite1.janet, etc.). You can
  run tests with `make test`. If you want to add a new test suite, simply add a file to
  the test folder and make sure it is run when`make test` is invoked.
* Be consistent with the style. For C this means follow the indentation and style in
  other files (files have MIT license at top, 4 spaces indentation, no trailing whitespace, cuddled brackets, etc.)
  For janet code, the use lisp indentation with 2 spaces. One can use janet.vim to
  do this indentation, or approximate as close as possible.

## Suggesting Changes

To suggest changes, open an issue on GitHub. Check GitHub for other issues
that may be related to your issue before opening a new suggestion. Suggestions
put forth without code will be considered, but not necessarily implemented in any
timely manner. In short, if you want extra functionality now, then build it.

* Include a good description of the problem that is being solved
* Include descriptions of potential solutions if you have some in mind.
* Add the appropriate tags to the issue. For new features, add the `enhancement` tag.