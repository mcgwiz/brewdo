Changelog
====

1.0
----

-   Initial release.

2.0
----

-   Modified chdir behavior.  Formerly, brewdo would unconditionally
    change to the root directory before switching to the sandbox user
    and performing sandbox actions.  Now, after switching to the
    sandbox user, brewdo tests to see if it can chdir to the current
    working directory, and only changes to the root directory if it
    cannot.  Fixes issue #7.

-   Minor documentation updates.

2.0.1
----

-   Updated documentation and Vagrant setups for Yosemite and Mavericks
    support.

-   Updated documentation with a working installation routine (sorry
    about that!)  Fixes issue #10.

