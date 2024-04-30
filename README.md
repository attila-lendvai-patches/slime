What
----

This is my fork of [Slime](https://github.com/slime/slime/). It
contains substantial improvements that were rejected by the
then-maintainer and are preserved here.


How
---

My commits are in the `hu.dwim.[date]` branches, and the latest one is
in the `hu.dwim` branch (which is the default branch of my fork). I
usually made a copy prior to rebasing my branch, hence the recorded
meta-history in the branch name.

The more time (upstream commits) passes between two rebases, the more
work it is/was to forward-port my changes. And with each rebase there
is a risk of introducing bugs.


Status
------

For the time being I'm not working much in Common Lisp, and thus I stopped
rebasing these poor stray commits of mine. It is a pity, because some of
them are really useful features, or bug fixes, and they are bitrotting
away with each new commit to the official Slime repo.


Future
------

I may return to extensive hacking in CL in the future, and I may end
up forward porting and resubmitting my commits... but right now this
doesn't seem probable, so no promises. If you get inspired by one of
these poor stray commits, then by all means go ahead with whatever
you're up to!
