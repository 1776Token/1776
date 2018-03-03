Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in configure
and tests weren't explicitly disabled.

After configuring, they can be run with 'make check'.

To run the 1776d tests manually, launch src/test/test_1776 .

To add more 1776d tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the test/ directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the 1776-qt tests manually, launch src/qt/test/1776-qt_test

To add more 1776-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.
