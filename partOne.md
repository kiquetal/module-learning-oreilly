### Dependency Graph

	For runtime and compile time.

	code -> package -> module -> jar

	You always say what packages you export
	You always say what module syou require or need

### For testing and learning

	java -d /tmp/classes Sample.java
	java -classpath /tmp/classes Sample

	java -d output/classes `find first -name *.java`
	jar -c -f output/mlib/first.jar -C /output/classes


