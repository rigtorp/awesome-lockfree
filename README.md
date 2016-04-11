# Awesome Lock-Free

A collection of resources on wait-free and lock-free programming.

## Libraries

* [Boost.Lockfree](http://www.boost.org/doc/libs/1_60_0/doc/html/lockfree.html) - Boost lock-free data structures.
* [ConcurrencyKit](https://github.com/concurrencykit/ck) - Concurrency primitives.
* [Folly](https://github.com/facebook/folly) - Facebook Open-source Library (has good implementation of MPMC queue).
* [Junction](https://github.com/preshing/junction) - Concurrent data structures in C++.
* [MPMCQueue](https://github.com/rigtorp/MPMCQueue) - A bounded multi-producer multi-consumer lock-free queue written in C++11.
* [SPSCQueue](https://github.com/rigtorp/SPSCQueue) - A bounded single-producer single-consumer wait-free and lock-free queue written in C++11.
* [Seqlock](https://github.com/rigtorp/Seqlock) - Implementation of Seqlock in C++.
* [Userspace RCU](http://liburcu.org/) - liburcu is a userspace RCU (read-copy-update) library.
* [libcds](https://github.com/khizmax/libcds) - A C++ library of Concurrent Data Structures.

## Websites

* [1024cores](http://www.1024cores.net/) - Dmitry Vyukov's website on lock-free programming.
* [LMAX Disruptor](https://lmax-exchange.github.io/disruptor/)
* [Wikipedia: Non-blocking algorithm](https://en.wikipedia.org/wiki/Non-blocking_algorithm)
* [Wikipedia: Read-copy-update](https://en.wikipedia.org/wiki/Read-copy-update)
* [Wikipedia: Seqlock](https://en.wikipedia.org/wiki/Seqlock)

## Blogs

* [Concurrency Freaks](http://concurrencyfreaks.blogspot.com/) - A web site dedicated to Concurrent algorithms and patterns.
* [Mechanical Sympathy](http://mechanical-sympathy.blogspot.com/)
* [Preshing on Programming](http://preshing.com/)
* [Sutter's Mill](http://herbsutter.com/) - Herb Sutter on software development.

## Papers

* [A Tutorial Introduction to the ARM and POWER Relaxed Memory Models][http://www.cl.cam.ac.uk/~pes20/ppc-supplemental/test7.pdf]
* [Simple, Fast, and Practical Non-Blocking and Blocking Concurrent Queue Algorithms](http://www.research.ibm.com/people/m/michael/podc-1996.pdf) - The Michael - Scott Queue
* [x86-TSO: A Rigorous and Usable Programmer’s Model for x86 Multiprocessors][http://www.cl.cam.ac.uk/~pes20/weakmemory/cacm.pdf]

## Talks

* [CppCon 2014: Herb Sutter "Lock-Free Programming (or, Juggling Razor Blades), Part I"](https://www.youtube.com/watch?v=c1gO9aB9nbs)
* [CppCon 2014: Herb Sutter "Lock-Free Programming (or, Juggling Razor Blades), Part II"](https://www.youtube.com/watch?v=CmxkPChOcvw)
* [CppCon 2015: Fedor Pikus PART 1 “Live Lock-Free or Deadlock (Practical Lock-free Programming)"](https://www.youtube.com/watch?v=lVBvHbJsg5Y)
* [CppCon 2015: Fedor Pikus PART 2 "Live Lock-Free or Deadlock (Practical Lock-free Programming)"](https://www.youtube.com/watch?v=1obZeHnAwz4)
* [CppCon 2015: Michael Wong “C++11/14/17 atomics and memory model..."](https://www.youtube.com/watch?v=DS2m7T6NKZQ)
* [CppCon 2015: Paul E. McKenney “C++ Atomics..."](https://www.youtube.com/watch?v=ZrNQKpOypqU)
* [CppCon 2014: Tony Van Eerd "Lock-free by Example"](https://www.youtube.com/watch?v=Xf35TLFKiO8)
* [C++ and Beyond 2012: Herb Sutter - atomic<> Weapons, 1 of 2](https://channel9.msdn.com/Shows/Going+Deep/Cpp-and-Beyond-2012-Herb-Sutter-atomic-Weapons-1-of-2)
* [C++ and Beyond 2012: Herb Sutter - atomic<> Weapons, 2 of 2](https://channel9.msdn.com/Shows/Going+Deep/Cpp-and-Beyond-2012-Herb-Sutter-atomic-Weapons-2-of-2)
* ["Aeron: Open-source high-performance messaging" by Martin Thompson](https://www.youtube.com/watch?v=tM4YskS94b0)
* [Adventures with Concurrent Programming in Java: A Quest for Predictable Latency - Martin Thompson](https://www.youtube.com/watch?v=eKVpea51tvo)
* [Understanding the Disruptor, a Beginner's Guide to Hardcore Concurrency -Trisha Gee & Mike Barker](https://www.youtube.com/watch?v=DCdGlxBbKU4)

## About

This list was compiled by [Erik Rigtorp](http://rigtorp.se)
<[erik@rigtorp.se](mailto:erik@rigtorp.se)>.
