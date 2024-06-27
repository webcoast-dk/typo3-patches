# Use full MD5 hashes in indexed_search

This patch backports the functionality from TYPO3 CMS 13
https://docs.typo3.org/c/typo3/cms-core/main/en-us/Changelog/13.0/Breaking-102975-UseFullMd5HashesInIndexed_search.html#breaking-102975-use-full-md5-hashes-in-indexed-search

You need to apply both patches to their respective packages:
* `typo3/cms-core`: [core.diff](core.diff)
* `typo3/cms-indexed-search`: [indexed_search.diff](indexed_search.diff)