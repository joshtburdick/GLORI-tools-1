# GLORI-tools, with some patches

A fork of the [https://github.com/liucongcas/GLORI-tools](GLORI-tools m6A pipeline),
by Josh Burdick (`josh.t.burdick@gmail.com`).

It incorporates some fixes mentioned on the project's Issues page.

If you find issues, it may make the most sense to mention them on the upstream
project's page.

## Slurm scripts

It also includes two Slurm scripts, derived from the `README` file.
One generates the index, and the other processes one sample.

Both of these will need some configuration, and are fairly unpolished.

## Changelog
* 20250430: initial fork, incorporating various things mentioned on the project's Issues
page. (This also includes a fix to the call to `scipy.stats.binomtest` in `m6A_caller.py`.)

