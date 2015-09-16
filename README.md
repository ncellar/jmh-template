# JMH Template (Without Maven)

1. Get core and annotation processing JMH jar (use `make fetchpom`).
2. Add them to your classpath: in your IDE, or move them to `deps/jar` if using the Makefile.
3. Make sure annotation processing is enabled in your IDE (it is by default when using the command line).
4. Write your benchmarks.
4. Run your benchmarks.
5. Profit?

Useful reference:

http://hg.openjdk.java.net/code-tools/jmh/file/tip/jmh-samples/src/main/java/org/openjdk/jmh/samples/
