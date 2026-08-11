# Validate input before writing to storage

Config parsing was duplicated in three call sites. Now there is one loader with defaults in a single place.

Change #4 of 6 on branch `pr/20260811-115807-4-validate-input-before-writing-to-storage`.
