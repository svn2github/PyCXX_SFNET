Version: 7.0.2 (31-Oct-2016)

Add Py::Char ord() method to return the long value of a character.

Fix String::size() that could return twice the accual length.
This affected as_ucs4string() which would return a string with
its second half as uninitialised memory.
