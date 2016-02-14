# LZSSE
[LZSS](https://en.wikipedia.org/wiki/Lempel%E2%80%93Ziv%E2%80%93Storer%E2%80%93Szymanski) designed for a branchless SSE decompression implementation.

Three variants:
- LZSSE2, for high compression files with small literal runs.
- LZSSE4, for a more balanced mix of literals and matches.
- LZSSE8, for lower compression data with longer runs of matches.

