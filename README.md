# libplist

Convert a plist FILE from binary to XML format or vice-versa.

```
$ docker run -it --rm -v $PWD:/files usualoma/libplist plistutil -i /files/file.plist -o /files/file.xml.plist
$ docker run -it --rm -v $PWD:/files usualoma/libplist plistutil -i /files/file.xml.plist -o /files/file.plist
```
