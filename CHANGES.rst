=================================
Change log for gocept.pytestlayer
=================================

3.1 (unreleased)
================

- Use tox as testrunner.


3.0 (2016-04-14)
================

- Claim compatibility with py.test 2.9.x.

- Drop Python 2.6 support.

2.1 (2014-10-22)
================

- Update handling of keywords and doctest testnames for py.test-2.5.
  [wosc]

- Re-introduce ``gocept.pytestlayer.fixture.create()`` method, to allow giving
  created fixtures a non-random name, so other fixtures can depend on them.
  [tlotze, wosc]

- Generate session-scoped fixtures from layers in addition to class-scoped
  ones, if a session-scoped one is required somewhere, the class-scoped ones
  are simply ignored. [tlotze, wosc]


2.0 (2013-09-19)
================

- Remove need to explicitely create fixtures.
  [gotcha]

- Add ``plone.testing.layered`` test suites support.
  [gotcha]

- Made tests a bit more robust.
  [icemac]


1.0 (2013-08-28)
================

- Initial release.
  [tlotze, icemac, gotcha]