# TODO

We should close all these issues before rolling Gherkin 3 into Cucumber/SpecFlow.

- [ ] Error message with path
- [ ] Integration tests for `testdata/bad/*.feature` that verifies file path and error message
  - [x] C#
  - [x] Ruby
  - [ ] JavaScript
  - [ ] Java
- [ ] Implement compiler
  - Base it on the compiler in cucumber-ruby-core
  - Need `/testdata/good/*.feature.tescase.json` files
  - [ ] C#
  - [ ] Ruby
  - [ ] JavaScript
  - [ ] Java
- [ ] Custom NoSuchLanguageException error
  - [ ] C#
  - [x] Ruby
  - [ ] JavaScript
  - [ ] Java
- [ ] Initialise parser with language (allows for global language config)
  - [ ] C#
  - [ ] Ruby
  - [ ] JavaScript
  - [ ] Java
- [ ] Make the Parser.parse() return a generic type
  - [ ] C#
  - [x] Java
- [ ] Use JSON as the primary representation of the AST for comparison
  - [ ] C#
  - [x] Ruby
  - [x] JavaScript
  - [x] Java
- [ ] Remove the `testdata/good/*.ast` files
- [ ] Use the new `dialects.json` file
  - [ ] C#
    - [ ] Don't load JSON file from the file system, but from a resource embedded in the dll.
  - [x] Ruby
  - [x] JavaScript
  - [x] Java
  - [ ] Rename to `gherkin-languages.json`
  - [ ] Remove `i18n.json`
- [ ] Rename `title` or `text` to `name` (check wiki, maybe discuss again)
  - [ ] C#
  - [ ] Ruby
  - [ ] JavaScript
  - [x] Java