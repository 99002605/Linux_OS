Reader Writer Problem:

When a database is to be shared among several concurrent processes. Some of these processes may want only to read the database, whereas others may want to update (that is, to read and write) the database. Distinguish between the two types of processes is done by referring to the former as readers and to the latter as writers. If two readers access the shared data simultaneously, no adverse effects will result. However, if a writer and some other process (either a reader or a writer) access the database simultaneously, chaos may ensue.

To ensure that these difficulties do not arise, it require that the writers have exclusive access to the shared database while writing to the database. This synchronization problem is referred to as the readers-writers problem.

This program simulates a readers writers problem in C.

To Run the code:

make

./final


[![Codacy Badge](https://api.codacy.com/project/badge/Grade/0cd20e790e1249cd8bf811e685c16ef6)](https://app.codacy.com/manual/99002605/Linux_OS?utm_source=github.com&utm_medium=referral&utm_content=99002605/Linux_OS&utm_campaign=Badge_Grade_Settings)

![cppcheck-action](https://github.com/99002605/Linux_OS/workflows/cppcheck-action/badge.svg)

![C/C++ CI](https://github.com/99002605/Linux_OS/workflows/C/C++%20CI/badge.svg)

![Unit testing](https://github.com/99002605/Linux_OS/workflows/Unit%20testing/badge.svg)
