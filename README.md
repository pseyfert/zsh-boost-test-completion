[![Build Status](https://travis-ci.org/pseyfert/zsh-boost-test-completion.svg?branch=master)](https://travis-ci.org/pseyfert/zsh-boost-test-completion)
[![Licence: GPL v3](https://img.shields.io/github/license/pseyfert/zsh-boost-test-completion.svg)](LICENSE)

# zsh-boost-test-completion
tab completion for [Boost.Test](https://www.boost.org/doc/libs/1_69_0/libs/test/doc/html/index.html).

## USAGE

 * put the `_boosttest` in one of the directories in the `$fpath` variable.
 * modify to your tests. e.g. by putting the test executable name in the `#compdef` line or call in your shell `compdef _boosttest <testexecutablename>`.
 * environment parameter value expansion is in place like: `BOOST_TEST_LOGGER=⇥`. Not though for `BOOST_TEST_⇥`, yet.

## Contributing
Contributions are welcome.

This may be (but is not restricted to), bug reports, bug fixes, additions of missing functions.

## Maintenance

For reference, a record of the `--help` message of a Boost.Test application is kept in `reference.txt`, to compare to newer versions of Boost.Test.
