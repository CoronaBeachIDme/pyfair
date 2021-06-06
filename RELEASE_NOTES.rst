Release Notes
=============

Version 0.2-beta.0
------------------

* Change PERT derivations from `prvalence` version to more commonly user
  version
* Universally changed `mode` argument to `most_likely`
* Add FairJupyterShim class
* Tested against: python 3.8.3, matplotlib 3.2.2, numpy 1.18.5, pandas 1.0.5,
  scipy 1.5.0

Version 0.1-alpha.12
--------------------

* Data validation fixes for changes in 0.1-alpha.11

Version 0.1-alpha.11
--------------------

* Added support for different currency prefixes
* Fixed errant abbreviations for `input_data()`

Version 0.1-alpha.10
--------------------

* Corrected inappropriate validation of gamma values
* Added additional unit tests for FairDatabase

Version 0.1-alpha.9
-------------------

* Corrected erroneous Vulnerability calculation
* Updated links in README

Version 0.1-alpha.8
-------------------

* Fixed FairSimpleReport to allow for interactive generation

Version 0.1-alpha.7
-------------------

* More descriptive error messages from FairSimpleReport
* Documentation fixes
* Fixes to FairSimpleReport (specifically SLEM)
* Fix calculation_completed() to allow for directly input of Risk

Version 0.1-alpha.6
-------------------

* Fixed metadata of base report to auto-fetch names cross-platform
* Corrected erroneous statements in documentation related to Vulnerability

Version 0.1-alpha.5
-------------------

* Added raw_input() function and associated storage routines
* Improved PEP8 compliance

Version 0.1-alpha.4
-------------------

* Correct inappropriate Vulnerability calculation

Version 0.1-alpha.3
-------------------

* Testing and documentation completed for the `utility` and `report`
  modules.

Version 0.1-alpha.2
-------------------

* Testing and documentation completed for the `model` module

Version 0.1-alpha.1
-------------------

* Additional documentation for items in `report` and `utility` modules

Version 0.1-alpha.0
-------------------

* Initial release of pyfair containing the foundational `FairModel`,
  `FairMetaModel`, `FairSimpleReport`, `FairDatabase`, and `FairModelFactory`
  classes
