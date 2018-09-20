# mil-tester : A test suite for mil-tools

This repository contains a rough first cut at a tester suite
for mil-tools.  It is cobbled together from assorted old tests
for MIL and LC together with a small number of new tests.  Some
details in the ways that this test suite has been configured
were motivated more by the goal of testing the implementation
of tester than by the goal of testing mi-tools.  I hope this
will be a good starting point for a more substantial test suite,
but there is much room here for rationalizing, reorganizing,
and expanding the current version.

Basic requirements and instructions for use:

* Download and install `tester` (`git clone https://github.com/zipwith/tester.git`).

* Download and install `mil-tools` (`git clone https://github.com/habit-lang/mil-tools`) in a parallel repository (i.e., in `../mil-tools`).

* Run the tests by using `tester -r main`.

* Check the documentation for `tester` for basic information about how test cases are defined, and then follow the examples in the `main` folder to create new test cases.  (Not that it may be easier to create a new set of test cases, keeping `main` as a reference instead of modifying it directly.)

