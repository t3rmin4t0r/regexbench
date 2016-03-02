# regexbench

    java -cp  target/benchmarks.jar org.notmysock.benchmark.RegexBench
    
    Benchmark                       Mode  Cnt    Score    Error  Units
    RegexBench.testGreedyRegexHit   avgt    5  336.114 ± 17.920  ns/op
    RegexBench.testGreedyRegexMiss  avgt    5  453.165 ± 33.753  ns/op
    RegexBench.testLazyRegexHit     avgt    5   68.117 ±  2.742  ns/op
    RegexBench.testLazyRegexMiss    avgt    5  359.710 ± 21.904  ns/op
