# @doist/localForage

A patched version of [localforage](https://github.com/localForage/localForage).


## Changelogs

__Remove Safari version check in isIndexedDBValid__

The original implementation tried to identify "modern Safari" by
checking if support client has native support of 'fetch' function.

If client uses any sort of fetch polyfill, this approaches will block
all Safari from using IDB. This fix remove checking of "modern Safari"



