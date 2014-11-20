Changes
=======

2.4 (2014-11-20)
------------------

- Upgrade to MathJax 2.4.
- Jump package version to 2.4 to match MathJax's one.
  [simahawk]


1.1.1 (2013-02-05)
------------------

- Also do not use ResourceRegistry's caching mechanism for the MathJax.
  [thet]


1.1 (2013-01-15)
----------------

- Do not cook the MathJax Resource, otherwise ResourceRegistry doesn't include
  it, since it thinks it cannot be found. Also, insert it at the end, so that
  other resources can be better merged together.
  [thet]


1.0 (2013-01-14)
----------------

- Initial release
