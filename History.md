
0.1.13 / 2012-05-28
===================

  * Fixed string-based field selection.

0.1.12 / 2012-05-25
===================

  * Added package.json tags.
  * Added support for update with ids (fixes #4)

0.1.11 / 2012-05-22
===================

  * Added support for new objectids through `Collection#id`

0.1.10 / 2012-05-21
===================

  * Enhanced findAndModify default behavior for upserts.
  * Fixed findAndModify.

0.1.9 / 2012-05-16
==================

  * Bumped mongoskin

0.1.8 / 2012-05-12
==================

  * Fixed mongoskin version
  * Improved options docs section.

0.1.7 / 2012-05-08
==================

  * Added global and collection-level options.
  * Enabled safe mode by default.
  * Improved error handling in tests.
  * Fixed `update` callback with safe: false.

0.1.6 / 2012-05-06
==================

  * Added tests for `findById`.

0.1.5 / 2012-05-06
==================

  * Added `Collection` references to `Promise`s.
  * Fixed `findAndModify`.

0.1.4 / 2012-05-06
==================

  * Ensured insert calls back with a single object.
  * Ensured `insert` resolves promise in next tick.

0.1.3 / 2012-05-03
==================

  * Exposed `util`

0.1.2 / 2012-05-03
==================

  * Make `Collection` inherit from `EventEmitter`.

0.1.1 / 2012-04-27
==================

  * Added `updateById`.

0.1.0 / 2012-04-23
==================

  * Initial release.
