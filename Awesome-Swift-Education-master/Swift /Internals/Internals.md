#### **Internals**
- ARC
    - ARC + Swift [:page_facing_up:](https://medium.com/the-traveled-ios-developers-guide/arc-swift-d323535baecb#.td8gy7jid)
    + Swift Manual Retain/Release [:page_facing_up:](http://www.russbishop.net/swift-manual-retain-release)
    - ARC in depth [:page_facing_up:](https://sectionfive.net/blog/2015/03/31/arc-in-depth-part-i/) [:page_facing_up:](https://sectionfive.net/blog/2015/06/12/arc-in-depth-part-ii/)
    - ARC Exploration and pitfalls [:page_facing_up:](https://sectionfive.net/blog/2014/11/24/arc-exploration-and-pitfalls/)
    - Static vs Dynamic Linking [:page_facing_up:](http://www.thedotpost.com/2015/02/marius-rackwitz-static-vs-dynamic-linking)
    - ARC vs Garbage Collection [:page_facing_up:](http://typedarray.org/swift-arc-vs-flash-gc/)
    - Why Swift should drop ARC [:page_facing_up:](https://digitalleaves.com/blog/2014/07/memory-management-in-swift-a-lost-opportunity/)
    - Call By Name [:page_facing_up:](http://www.russbishop.net/swift-call-by-name)
    - Are Swift variables atomic? [:page_facing_up:](http://stackoverflow.com/questions/24157834/are-swift-variables-atomic)
    - Is there a reason that Swift array assignment is inconsistent (neither a reference nor a deep copy)? [:link:](http://stackoverflow.com/questions/24081009/is-there-a-reason-that-swift-array-assignment-is-inconsistent-neither-a-referen)
    - How does Swift implement ARC in property attributes? [:link:](http://stackoverflow.com/questions/24387634/how-does-swift-implement-arc-in-property-attributes)
    - Will ARC always make Swift slower than a language without any type of garbage collector like C++ or C? [:page_facing_up:](https://www.quora.com/Will-ARC-always-make-Swift-slower-than-a-language-without-any-type-of-garbage-collector-like-C++-or-C?srid=xrLC&share=e61ad115)
- Assembly
    - IR is better than assembly [:page_facing_up:](https://idea.popcount.org/2013-07-24-ir-is-better-than-assembly/)
    - iOS Assembly Tutorial: Understanding ARM [:page_facing_up:](https://www.raywenderlich.com/37181/ios-assembly-tutorial)
    - An ARM Build Farm with Jenkins [:page_facing_up:](http://dev.iachieved.it/iachievedit/an-arm-build-farm-with-jenkins/)
    - Swift for ARM Systems [:page_facing_up:](http://dev.iachieved.it/iachievedit/swift-for-arm-systems/)
- Build
    - Steps of a Swift Application Build [:link:](http://stackoverflow.com/a/25965909/2855836)
    - Build Configuration Management [:page_facing_up:](http://dev.iachieved.it/iachievedit/build-configuration-management-with-swift/)
    - Swift Byte Packing [:page_facing_up:](http://www.russbishop.net/packing-bytes-in-swift)
    - Swift Compilation Reporting at Tumblr [:page_facing_up:](https://engineering.tumblr.com/post/144151794436/swift-compilation-reporting-at-tumblr)
- Clang
    - Clang documentation [:link:](http://clang.llvm.org/docs/index.html)
    - Clang format for Xcode [:pencil:](https://github.com/travisjeffery/ClangFormat-Xcode)
    - fucking clang warnings [:link:](http://fuckingclangwarnings.com/)
    - Clang vs Other Open Source Compilers [:page_facing_up:](http://clang.llvm.org/comparison.html)
    - What is the difference between LLVM and Clang? [:page_facing_up:](https://www.quora.com/What-is-the-difference-between-LLVM-and-Clang)
    - A C++ to Swift Bridge implemented as a Clang Tool [:pencil:](https://github.com/sandym/swiftpp)
- Grammar
    - Implicit Member Expression [:link:](http://stackoverflow.com/a/35387593/2855836)
- LLVM Compiler
    - WWDC 2014: What's new in LLVM [:microphone:](http://devstreaming.apple.com/videos/wwdc/2014/417xx2zsyyp8zcs/417/417_whats_new_in_llvm.pdf) [:floppy_disk:](http://devstreaming.apple.com/videos/wwdc/2014/417xx2zsyyp8zcs/417/417_whats_new_in_llvm.pdf)
    + LLVM by Chris Lattner [:page_facing_up:](http://aosabook.org/en/llvm.html)
    + Swift Intermediate Language [:floppy_disk:](http://llvm.org/devmtg/2015-10/slides/GroffLattner-SILHighLevelIR.pdf)
    + Using the LLVM API With Swift [:page_facing_up:](http://lowlevelbits.org/how-to-use-llvm-api-with-swift/)
    - LLVM and Swift [:microphone:](https://www.youtube.com/watch?v=Ntj8ab-5cvE)
    - LLVM in Swift: Setup [:page_facing_up:](http://dduan.net/post/2015/10/lets-play-llvm-in-swift-setup/)
    - Kaleidoscope: Implementing a Parser and AST in LLVM [:page_facing_up:](http://llvm.org/docs/tutorial/LangImpl1.html) [:pencil2:](https://github.com/matthewcheok/Kaleidoscope)
    - Swift Object Name De-mangling [:page_facing_up:](https://www.securify.nl/blog/SFY20150302/hooking_swift_methods_for_fun_and_profit.html)
    - Hopper Swift Demangler [:pencil:](https://github.com/keith/hopper-swift-demangle)
    - How to use LLVM API with Swift [:page_facing_up:](http://lowlevelbits.org/how-to-use-llvm-api-with-swift/) [:page_facing_up:](http://lowlevelbits.org/how-to-use-llvm-api-with-swift-addendum/)
    - Swift Compiler [:page_facing_up:](https://www.accelebrate.com/blog/thinking-swift-part-ii/)
    - Parsing Mach-O files [:page_facing_up:](http://lowlevelbits.org/parse-mach-o-files/)
    - How to use LLVM C API with Swift [:page_facing_up:](https://fosdem.org/2016/schedule/event/llvm_c_swift/) [:page_facing_up:](https://github.com/AlexDenisov/swift_llvm)
    - Creating a Virtual Machine/Register VM [:page_facing_up:](https://en.wikibooks.org/wiki/Creating_a_Virtual_Machine/Register_VM_in_Swift)
    - What is LLVM and how does it differ from GCC? [:page_facing_up:](https://www.quora.com/What-is-LLVM-and-how-it-is-different-from-GCC)
    - Swift wrapper around LLVM [:pencil2:](https://github.com/bencochran/LLVM.swift)
    - Simple programming language written in Swift and compiled with LLVM [:pencil2:](https://github.com/bencochran/Kaleidoscope)
    - Swift wrapper around LLVM-C [:pencil:](https://github.com/bencochran/LLVM.swift)
- Memory
    - Exploring Swift's Dictionary Implementation [:page_facing_up:](http://ankit.im/swift/2016/01/20/exploring-swift-dictionary-implementation/)
    - Swift Memory Layout [:page_facing_up:](https://www.mikeash.com/pyblog/friday-qa-2014-07-18-exploring-swift-memory-layout.html)
    - Swift Struct Storage [:page_facing_up:](https://www.mikeash.com/pyblog/friday-qa-2016-01-29-swift-struct-storage.html)
    - Storage for Structs Opinionated Serialization With Generics [:microphone:](https://www.skilled.io/nickoneill/lets-code-storage-for-structs)
    - Bitcode Demystified [:page_facing_up:](http://lowlevelbits.org/bitcode-demystified/)
    - Memory management using Swift and Objective-C [:page_facing_up:](http://www.ibm.com/developerworks/library/mo-ios-memory/)
    - Swift Memory and Concurrency Model [:page_facing_up:](http://fossies.org/linux/misc/swift-swift-2.2-SNAPSHOT-2015-12-01-b.tar.gz/swift-swift-2.2-SNAPSHOT-2015-12-01-b/docs/proposals/archive/Memory%20and%20Concurrency%20Model.rst)
    - Where is my variable being stored? [:link:](http://stackoverflow.com/questions/31987566/where-is-my-variable-being-stored-swift)
    - Minimizing your app's Memory Footprint [:page_facing_up:](ttps://developer.apple.com/library/ios/technotes/tn2434/_index.html)
- Optimizations
    - The Importance of Being Final [:page_facing_up:](http://blog.human-friendly.com/the-importance-of-being-final)
    - Switch Statement Optimizations [:link:](http://stackoverflow.com/questions/25284522/switch-statement-optimization-swift)
    - Swift Whole Module Optimization [:page_facing_up:](http://useyourloaf.com/blog/swift-whole-module-optimization/)
    - Increasing Performance by Reducing Dynamic Dispatch [:microphone:](https://developer.apple.com/swift/blog/?id=27)
    - Dynamic Dispatch and Whole Module Optimization [:page_facing_up:](http://useyourloaf.com/blog/dynamic-dispatch-and-whole-module-optimization/)
    - How Swift uses introSort [:page_facing_up:](http://stackoverflow.com/questions/27677026/swift-sorting-algorithm-implementation)
    - Optimizing Swift Performance [:microphone:](https://developer.apple.com/videos/play/wwdc2015-409/)
    - Functional Style - 50x Speed boost from changing 1 Keyword [:page_facing_up:](http://blog.human-friendly.com/optimising-swift-with-functional-style-50x-speed-boost-from-changing-1-keyword)
    - Launch time performance optimization [:page_facing_up:](http://www.avanderlee.com/optimization/launch-time-performance-optimization/)
    - Meaning of the LLVM Optimization Levels [:link:](http://stackoverflow.com/questions/21447377/meaning-of-the-llvm-optimization-levels)
    - ARC Optimization for Swift [:pencil:](https://github.com/apple/swift/blob/master/docs/ARCOptimization.rst)
    - High Level SIL Optimizations [:pencil:](https://github.com/apple/swift/blob/master/docs/HighLevelSILOptimizations.rst)
    - The Effect of Dependency Structure on iOS Launch Times [:page_facing_up:](https://engineering.tumblr.com/post/144507330193/peeking-into-a-black-box-the-effect-of)
- Performance
    - Swift Performance [:floppy_disk:](http://blog.human-friendly.com/swift-performance-iosdevuk) [:page_facing_up:](http://www.swift-studies.com/blog/2014/7/8/learning-about-swift-performance)[:pencil:](https://github.com/koher/swift-performance-experiment)
    - Swift 2 Under the Hood [:floppy_disk:](https://speakerdeck.com/alblue/swift-2-under-the-hood-gotober-2015)
    - Swift Compiler Diagnostics [:page_facing_up:](http://oleb.net/blog/2015/08/swift-compiler-diagnostics/)
    - Swift: Performance of Inline Code versus Instance Methods versus Class Methods [:page_facing_up:](http://flexmonkey.blogspot.com/2014/09/swift-performance-of-inline-code-versus.html)
    - Simple Swift.String Performance Test [:pencil2:](https://github.com/bnickel/Simple-Swift.String-Performance-Test)
    - Secret of Swift Performance [:page_facing_up:](https://medium.com/swift-programming/secret-of-swift-performance-fcc5d2a437a8#.q0cnnqxat) [:page_facing_up:](https://medium.com/swift-programming/secret-of-swift-performance-a8ee86060843#.i6p6554gk)
    - Writing High Performance Swift Code [:link:](https://github.com/apple/swift/blob/master/docs/OptimizationTips.rst)
    - Swift Single Soutce [:pencil:](https://github.com/apple/swift/tree/master/benchmark/single-source)
    - 10 thousand times faster Swift [:page_facing_up:](https://medium.com/@icex33/10-thousand-times-faster-swift-737b1accd973#.92zevwqyq)
    - Why Swift is swift [:microphone:](https://www.skilled.io/purpleyay/why-swift-is-swift)
- Preprocessing
    - Preprocessing in Swift [:link:](http://stackoverflow.com/questions/24369272/swift-ios-deployment-target-command-line-flag)
    - Preprocessor Macros [:link:](http://stackoverflow.com/questions/24111854/in-absence-of-preprocessor-macros-is-there-a-way-to-define-practical-scheme-spe)
    - Parsing Mach-O Files [:page_facing_up:](http://lowlevelbits.org/parse-mach-o-files/)
    - -Xfront [:page_facing_up:](http://www.robertvojta.com/2015/06/30/swift-hidden-options/)
    - Change your API endpoint/environment using Xcode Configurations in Swift [:page_facing_up:](https://medium.com/@danielgalasko/change-your-api-endpoint-environment-using-xcode-configurations-in-swift-c1ad2722200e#.a1lggp7pb)
- SIL and swiftc
    - Official SIL Page [:pencil:](https://github.com/apple/swift/blob/master/docs/SIL.rst)
    - - 🖇Introduction to Swift Intermediate Language [:video_camera:](https://www.youtube.com/watch?feature=youtu.be&utm_medium=email&v=NH-qIKOoKgA)
    - Exploring SIL and swiftc [:page_facing_up:](http://swiftc.io/)
    - swift vs swiftc [:page_facing_up:](http://owensd.io/2015/01/14/swift-vs-swiftc.html)
    - SIMD (Single Instruction Multiple Data) [:page_facing_up:](http://www.russbishop.net/swift-2-simd)
    - @convention [:page_facing_up:](http://stackoverflow.com/questions/30740560/new-conventionc-in-swift-2-how-can-i-use-it)
    - Introspecting Swift [:floppy_disk:](https://speakerdeck.com/jpsim/introspecting-swift)
    - Unsafe Swift [:floppy_disk:](https://speakerdeck.com/realm/unsafe-swift)
    + Type Introspection and demangling [:page_facing_up:](http://ericasadun.com/2014/06/16/swift-more-than-you-probably-want-to-know-about-type-introspection/)
    - The mysterious builtin module [:page_facing_up:](http://ankit.im/swift/2016/01/12/swift-mysterious-builtin-module/)
    - SIL Optimizations [:pencil:](https://github.com/apple/swift/blob/master/docs/HighLevelSILOptimizations.rst)