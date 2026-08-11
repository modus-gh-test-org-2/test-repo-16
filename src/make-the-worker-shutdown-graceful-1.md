# Make the worker shutdown graceful

Config parsing was duplicated in three call sites. Now there is one loader with defaults in a single place.

Change #1 of 6 on branch `pr/20260811-115807-1-make-the-worker-shutdown-graceful`.
