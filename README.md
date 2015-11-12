pytest-snapci
===============

py.test Snap-CI Plugin

When running tests under Snap-CI you can run on multiple machines. Snap-CI sets
environment variables to indicate which machine you are running on. This plugin
ensures tests are split across the machines by reading these variables.

Once installed py.test will look for SNAP_WORKER_TOTAL and SNAP_WORKER_INDEX
environment variables to partition tests with.
