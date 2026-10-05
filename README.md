# Awesome Lock-Free

A collection of resources on wait-free and lock-free programming.

:fire: :fire: :fire: Even better resource from [MattPD](https://github.com/MattPD): [C++ links: atomics, lock free, memory model](https://github.com/MattPD/cpplinks/blob/master/atomics.lockfree.memory_model.md).

## Libraries

* [Boost.Lockfree](http://www.boost.org/doc/libs/1_60_0/doc/html/lockfree.html) - Boost lock-free data structures.
* [ConcurrencyKit](https://github.com/concurrencykit/ck) - Concurrency primitives.
* [crossbeam](https://github.com/crossbeam-rs/crossbeam) - Rust library for concurrent programming.
* [Folly](https://github.com/facebook/folly) - Facebook Open-source Library (has good implementation of MPMC queue).
* [Junction](https://github.com/preshing/junction) - Concurrent data structures in C++.
* [MPMCQueue](https://github.com/rigtorp/MPMCQueue) - A bounded multi-producer multi-consumer lock-free queue written in C++11.
* [SPSCQueue](https://github.com/rigtorp/SPSCQueue) - A bounded single-producer single-consumer wait-free and lock-free queue written in C++11.
* [Seqlock](https://github.com/rigtorp/Seqlock) - Implementation of Seqlock in C++.
* [Userspace RCU](http://liburcu.org/) - liburcu is a userspace RCU (read-copy-update) library.
* [libcds](https://github.com/khizmax/libcds) - A C++ library of Concurrent Data Structures.
* [liblfds](https://liblfds.org/) - portable, license-free, lock-free data structure library written in C.
* [xenium](https://github.com/mpoeter/xenium) - A C++ library providing various concurrent data structures and reclamation schemes.
* [lockfree](https://github.com/DNedic/lockfree) - A collection of lock-free data structures written in standard C++11. Configurable and embedded friendly.

## Websites

* [1024cores](http://www.1024cores.net/) - Dmitry Vyukov's website on lock-free programming.
* [LMAX Disruptor](https://lmax-exchange.github.io/disruptor/)
* [Wikipedia: Non-blocking algorithm](https://en.wikipedia.org/wiki/Non-blocking_algorithm)
* [Wikipedia: Read-copy-update](https://en.wikipedia.org/wiki/Read-copy-update)
* [Wikipedia: Seqlock](https://en.wikipedia.org/wiki/Seqlock)

## Blogs

* [Concurrency Freaks](http://concurrencyfreaks.blogspot.com/) - A web site dedicated to Concurrent algorithms and patterns.
* [Dan Luu](http://danluu.com/) - Lots of info on modern computer architecture.
* [Locking in Webkit](https://webkit.org/blog/6161/locking-in-webkit/)
* [Mechanical Sympathy](http://mechanical-sympathy.blogspot.com/)
* [Paul E. McKenney](http://paulmck.livejournal.com/)
* [Preshing on Programming](http://preshing.com/)
* [Sutter's Mill](http://herbsutter.com/) - Herb Sutter on software development.
* [Paul Khuong](https://www.pvk.ca/Blog/archives/)

## Books

* *Paul E. McKenney*. [Is Parallel Programming Hard, And, If So, What Can You Do About It?](https://www.kernel.org/pub/linux/kernel/people/paulmck/perfbook/perfbook.html)
* *Maurice Herlihy and Nir Shavit*. [The Art of Multiprocessor Programming](https://dl.acm.org/citation.cfm?id=2385452)

## Papers

* [A Tutorial Introduction to the ARM and POWER Relaxed Memory Models](http://www.cl.cam.ac.uk/~pes20/ppc-supplemental/test7.pdf)
* *Paul E. McKenney*. [Memory Barriers: a Hardware View for Software Hackers](http://irl.cs.ucla.edu/~yingdi/web/paperreading/whymb.2010.06.07c.pdf).
* [Simple, Fast, and Practical Non-Blocking and Blocking Concurrent Queue Algorithms](https://www.cs.rochester.edu/u/scott/papers/1996_PODC_queues.pdf) - The Michael - Scott Queue
* *Ulrich Drepper*. [What Every Programmer Should Know About Memory](https://www.akkadia.org/drepper/cpumemory.pdf)
* [x86-TSO: A Rigorous and Usable Programmer’s Model for x86 Multiprocessors](http://www.cl.cam.ac.uk/~pes20/weakmemory/cacm.pdf)

## Talks

* [CppCon 2014: Herb Sutter "Lock-Free Programming (or, Juggling Razor Blades), Part I"](https://www.youtube.com/watch?v=c1gO9aB9nbs)
* [CppCon 2014: Herb Sutter "Lock-Free Programming (or, Juggling Razor Blades), Part II"](https://www.youtube.com/watch?v=CmxkPChOcvw)
* [CppCon 2015: Fedor Pikus PART 1 “Live Lock-Free or Deadlock (Practical Lock-free Programming)"](https://www.youtube.com/watch?v=lVBvHbJsg5Y)
* [CppCon 2015: Fedor Pikus PART 2 "Live Lock-Free or Deadlock (Practical Lock-free Programming)"](https://www.youtube.com/watch?v=1obZeHnAwz4)
* [CppCon 2015: Michael Wong “C++11/14/17 atomics and memory model..."](https://www.youtube.com/watch?v=DS2m7T6NKZQ)
* [CppCon 2015: Paul E. McKenney “C++ Atomics..."](https://www.youtube.com/watch?v=ZrNQKpOypqU)
* [CppCon 2014: Tony Van Eerd "Lock-free by Example"](https://www.youtube.com/watch?v=Xf35TLFKiO8)
* [CppCon 2016: Fedor Pikus "The Speed of Concurrency: is lock-free faster?"](https://www.youtube.com/watch?v=9hJkWwHDDxs)
* [CppCon 2016: Hans Boehm “Using weakly ordered C++ atomics correctly"](https://www.youtube.com/watch?v=M15UKpNlpeM)
* [CppCon 2017: Fedor Pikus “C++ atomics, from basic to advanced. What do they really do?”](https://www.youtube.com/watch?v=ZQFzMfHIxng)
* [CppCon 2017: Fedor Pikus “Read, Copy, Update, then what? RCU for non-kernel programmers”](https://www.youtube.com/watch?v=rxQ5K9lo034)
* [CppCon 2017: P. McKenney, M. Michael & M. Wong “Is Parallel Programming still hard? PART 1 of 2”](https://www.youtube.com/watch?v=YM8Xy6oKVQg)
* [CppCon 2017: P. McKenney, M. Michael & M. Wong “Is Parallel Programming still hard? PART 2 of 2”](https://www.youtube.com/watch?v=74QjNwYAJ7M)
* [CppCon 2018: “The Landscape and Exciting New Future of Safe Reclamation for High Performance”](https://www.youtube.com/watch?v=nvfzQAUpunI)
* [C++ and Beyond 2012: Herb Sutter - atomic<> Weapons, 1 of 2](https://channel9.msdn.com/Shows/Going+Deep/Cpp-and-Beyond-2012-Herb-Sutter-atomic-Weapons-1-of-2)
* [C++ and Beyond 2012: Herb Sutter - atomic<> Weapons, 2 of 2](https://channel9.msdn.com/Shows/Going+Deep/Cpp-and-Beyond-2012-Herb-Sutter-atomic-Weapons-2-of-2)
* ["Aeron: Open-source high-performance messaging" by Martin Thompson](https://www.youtube.com/watch?v=tM4YskS94b0)
* [Adventures with Concurrent Programming in Java: A Quest for Predictable Latency - Martin Thompson](https://www.youtube.com/watch?v=eKVpea51tvo)
* [Understanding the Disruptor, a Beginner's Guide to Hardcore Concurrency -Trisha Gee & Mike Barker](https://www.youtube.com/watch?v=DCdGlxBbKU4)

## About

This list was compiled by [Erik Rigtorp](http://rigtorp.se)
<[erik@rigtorp.se](mailto:erik@rigtorp.se)>.
