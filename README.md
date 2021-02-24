
This is an example using [git subtree](https://www.atlassian.com/git/tutorials/git-subtree).

This is kind of the header doc to the whole set of repos. You can add a link
here to the index of the documentation/diary like so:

* [code1](code1/README.md)
* [code2](code2/README.md)

As opposed to the submodule method, subtree links do work from online.

The child repos can be developed independently of this one. 

People will ideally need permissions for this catchall repository as well as
the particular module they are developing.

There doesn't seem to be a way to only include a particular subdirectory
of one of the submodules in this one.

With git-subtree you'll need to reference the various remote urls directly somewhere.
Subtree doesn't store these anywhere. Docs recommend storing subtree references
as remotes. Remotes don't necessarily copy on clone though...

