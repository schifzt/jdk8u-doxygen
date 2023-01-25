# jdk8u-doxygen

doxygenを用いて[jdk8u](https://github.com/openjdk/jdk8u)のソースコードからOpenJDK8の日本語ドキュメントを生成する

## Directory structure
- target source code: `jdk8u/jdk/src/share/classes/java/*`
- generated document: `generated-doc/`

## Command
Invoke the following commnad at the root directory.
It will take about 20 minutes to generate the document.
```
$ doxygen Doxyfile
```
