# Overview

Allow to index and search files as https://www.voidtools.com/ (works in service as admin mode only) instantly.

Written in Rust for safety and low resources consumtion. So C# 10 is also viable.

I will allow to bookmark files using # by creating folder with links with files renamed to include #
https://schinagl.priv.at/nt/hardlinkshellext/hardlinkshellext.html

It will allow to search # tags like chrome-extension://edpeidcfjfepdgdjnodefckgdjbigem/index.html

chrome-extension://edpeidcfjfmepdgdjnodefckgdjbigem/index.html

Also it will allow to tag via https://github.com/Dijji/FileMeta, so no name changes neeed.

Bookmarked links are possible to sync via syncthing

# Why it different?

- written in safe and fast language to get best of speed and security languages.
- does not stores metadata file along existing file, neither changes existing file, so hash of file is same and sync tools are not polluted
- It does not have any sync or content indexing mechanisms
