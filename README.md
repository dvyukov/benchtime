# benchtime
Outputs time results in Go benchmark format

```
$ benchtime go install std
BenchmarkTime 1 138625590 ns/op
BenchmarkUserTime 1 167742000 ns/op
BenchmarkSysTime 1 28755000 ns/op
BenchmarkCpuLoad 1 141.75 ns/op # %CPU
BenchmarkMaxRSS 1 9949184 ns/op # bytes
```

The output can be used with `benchcmp` and `benchstat` commands.
