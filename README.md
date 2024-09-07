Code snippits
  >>> from progressbar import ProgressBar
  >>> p = ProgressBar()
  >>> print p
  [>............] 0%
  >>> p + 1
  >>> print p
  [=>...........] 10%
  >>> p + 9
  >>> print p
  [============>] 0%
