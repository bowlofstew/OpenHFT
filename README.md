OpenHFT Parent Module
=====================

Parent module to include active modules

Key Modules
===========

Java Thread Affinity - Declaritive binding of threads to individual CPUs.  Using in combination with isocpus= on Linux, you can reduce scheduling jitter from 5 ms to 10 micro-seconds.

Java Lang - Low level IO such as 64-bit access to off heap memory. Used by Chronicle and Huge Collections

Java Chroncicle - Low latency IPC. Supports 0.1 micro-second persisted IPC between processes and signle digit persisted replication between machines. Less than 15 micro-seconds between machines, 99% of the time for real messages.

HugeCollections - Off heap hash maps.  HugeHashMap is a process private, off heap storage supporting over one billon key-values. SharedHashMap is a the same shared between processes and is persisted.  SharedHashMap supports tens of millions operations per second, for hundreds of millions of keys-values, with no GC pressure (trivial garbage produced)

Java Runtime Compiler - Wrapper for the Java Compiler API to support in memory compilation.  Give it is String of Java code and it will give you a Class.

Tools
=====
OpenHFT recommends;

[![IntelliJ](http://www.jetbrains.com/img/logos/logo_intellij_idea.png)](http://www.jetbrains.com/idea/)

[![YourKit](http://www.red-soft.biz/files/downloads/partners_logo/YourKit_index_logo.gif)](http://www.yourkit.com/overview/)

Other commercial profilers can be used.  VisualVM creates too much noise to be useful at this level.

