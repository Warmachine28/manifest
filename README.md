AOSP+RRO MarshMallow
===========

To initialize your local repository using the AOSP-RRO trees, use a command like this:
````bash
repo init -u git://github.com/AOSP-RRO/manifest.git -b marshmallow
```
Then to sync up:
````bash
repo sync
```
Finally to build:
````bash
./build.sh device_codename
```
Example:
````bash
./build.sh falcon
./build.sh titan
```

### repo sync
[![Build Status](http://blazingphoenix.in:8484/buildStatus/icon?job=AOSP-RRO-Sync&build=2)](http://blazingphoenix.in:8484/job/AOSP-RRO-Sync/2/)

### rom build
[![Build Status](http://blazingphoenix.in:8484/buildStatus/icon?job=AOSP-RRO)](http://blazingphoenix.in:8484/job/AOSP-RRO/)
