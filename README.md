pymongo-basic-profiler
======================
Each version of this package is quite closely tied to individual an `pymongo`
version (or a small range of versions), as it relies on `pymongo` internals.

Supported `pymongo` version: 3.7.1

Supported operations:

* `save`
* `delete_one`
* `delete_many`
* `insert`
* `insert_one`
* `find`
* `find_one`
* `remove`
* `replace_one`
* `update`
* `update_one`

Unsupport operations

* `insert_many`

Found a similar project?
------------------------
I have not been able to find a project that does the same.
If you find one -- please let me know. There's most likely no reason to maintain
two libraries with the same purpose.

Projects with internals similar to this one
-------------------------------------------
The following projects also monkey patch `pymongo` in order to track queries:

* [Flask Debug Toolbar MongoDB Panel](https://github.com/bcarlin/flask-debugtoolbar-mongo)
* [mongodog](https://github.com/Paulius-Maruska/mongodog)
* [mongomock_mate-project](https://github.com/MacHu-GWU/mongomock_mate-project/tree/master/mongomock_mate)
