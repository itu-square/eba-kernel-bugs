# Double lock kernel bugs

A benchmark of _C Single-Thread Use-After-Free_ bugs.

All the files come from patches to the Linux kernel found in the `git log` of the kernel repository at [https://github.com/torvalds/linux](https://github.com/torvalds/linux).

This sample has been collected using the `git log --grep="use after free"` git command within the Linux kernel repository spanning the timeframe from `Nov 13, 2019` to `May 26, 2020`. 

The filename hashes are the parent commit to a patch of a bug. In order to find the patch of the bug, explore the child commit(s) of the commit with the filename hash.

The two folders contain:
- `preprocessed`: Fully preprocessed files.
- `raw`: Raw un-preprocessed source files.
