go-deepcopy
===========

A polymorphic DeepCopy for Go using reflection.

USERS BEWARE! This fix is held together by chewing gum and wire. In particular,
there is a heisenbug that triggers if the copious amounts of debug-prints are
removed. You've been warned.

It is a fork of
[code.google.com/r/jeffallen-fixes/exp/deepcopy](https://code.google.com/r/jeffallen-fixes/source/browse/#hg%2Fexp%2Fdeepcopy)
which in turn is a clone of
[code.google.com/p/rog-go/exp/deepcopy](http://code.google.com/p/rog-go/source/browse/#hg%2Fexp%2Fdeepcopy),
but updated for the recent api changes to `unsafe` and `reflection`.

It is by transitivity licensed under the BSD 3-clause license.
