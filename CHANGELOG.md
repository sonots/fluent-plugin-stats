## 0.4.0 (2017/09/15)

Enhancements:

* Support v0.14

## 0.3.6 (2014/12/3)

Enhancements:

* Do not compute average for zero_emit message
  * ToDo: Still, we should get the denominator to compute average from input json field

## 0.3.5 (2014/08/07)

Enhancements:

* Add `remove_tag_slice` option
* Add `aggregate out_tag` option

## 0.3.4 (2014/04/12)

Enhancements:

* Add `add_tag_suffix`, and `remove_tag_suffix` options

## 0.3.3 (2014/02/04)

Enhancement:

* Support `log_level` option of Fleuntd v0.10.43

## 0.3.2 (2014/01/24)

Fixes

- Fix the case when input record keys are symbols

## 0.3.1 (2014/01/02)

Fixes

- Trivial fix not to emit empty {} message

## 0.3.0 (2013/12/27)

Changes

- Rename fluent-plugin-stats from fluent-plugin-calc

## 0.2.0 (2013/12/12)

Enhancement:

- Add `remove_tag_prefix` option

## 0.1.2 (2013/10/10)

Enhancement:

- Add `zero_emit` option to emit 0 on the next interval like datacounter plugin

## 0.1.1 (2013/09/02)

Fixes

- Fix the case when not record is found.

## 0.1.0 (2013/09/02)

Changes

- Accept string data by `to_f`.

## 0.0.5 (2013/09/02)

Enhancement:

- add `sum_keys`, `max_keys`, `min_keys`, `avg_keys`.

## 0.0.4 (2013/08/30)

Enhancement:

- add `sum_suffix`, `max_suffix`, `min_suffix`, `avg_suffix`.

## 0.0.2 (2013/05/06)

Bugfixes:

- Fix so that @avg can be an option

## 0.0.1 (2013/05/05)

First version

