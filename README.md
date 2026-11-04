sha256 Implemented in Bash
=======================

Pure bash implementation of the sha256 checksum algorithm

Usage
----

```
./sha256 file.txt
./sha256 < file.bin
echo 'hello' | ./sha256
DEBUG=1 ./sha256 file.txt
```

Testing
-------

Run the basic test suite:

```
./test-sha256 [path/to/sha256]
```

Run the comprehensive edge-case and correctness verification suite:

```
./verify-sha256 [path/to/sha256]
./verify-sha256 --quick
./verify-sha256 --filter "Boundary"
```

YouTube
-------

Watch me build this live on YouTube.

<a href="https://www.youtube.com/watch?v=GXibFvdKiO8"><img
alt="Bash sha256 YouTube Thumbnail"
src="https://i.ytimg.com/vi/GXibFvdKiO8/maxresdefault.jpg"
/></a>

License
-------

MIT License
