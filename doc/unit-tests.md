Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in configure
and tests weren't explicitly disabled.

After configuring, they can be run with 'make check'.

To run the npaynetworkd tests manually, launch src/test/test_npaynetwork .

To add more npaynetworkd tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the test/ directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the npaynetwork-qt tests manually, launch src/qt/test/npaynetwork-qt_test

To add more npaynetwork-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.
