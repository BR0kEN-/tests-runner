# Tests Runner

The script that can help you to manage running your tests. The detailed description of the project is available in the [Automate running tests in different languages on Travis CI](https://cikit.tools/blog/travis-tests-automation) publication.

## Usage

- Create a directory with tests.
- Group tests within subfolders. Name each directory as an interpreter that should run the tests.
- Put an `.extension` file inside of each subfolder. The file must contain an extension of test files within the directory.
- Name files with tests following the `[a-z]` pattern. All the rest will not be processed by the runner and may be used internally.

For more detailed usage explanation please read the [blog post](https://cikit.tools/blog/travis-tests-automation).
