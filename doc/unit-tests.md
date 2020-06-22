Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in configure
and tests weren't explicitly disabled.

After configuring, they can be run with 'make check'.

To run the nakasd tests manually, launch src/test/test_nakas .

To add more nakasd tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the test/ directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the nakas-qt tests manually, launch src/qt/test/nakas-qt_test

To add more nakas-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.
