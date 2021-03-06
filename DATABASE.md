# The following are timings from various CPUs with default configurations

### i7-4710HQ
```
discovered Intel(R) Core(TM) i7-4710HQ CPU @ 2.50GHz: 8 logical CPU(s), 4 physical, 2 thread(s) per core
measuring memory perf across CPU(s) with explicit memory mappings
running 32 trial(s) on a space of 128.00 MiB with 4 thread(s) per trial run
trial 32 of 32 [%100.00] (wr 0.045994 sec, rd 0.039005 sec)
thread averages:
  1 (wr 0.212761 sec, rd 0.190548 sec)
  2 (wr 0.153349 sec, rd 0.124817 sec)
  3 (wr 0.104419 sec, rd 0.077651 sec)
  4 (wr 0.046590 sec, rd 0.019056 sec)
total average: (wr 2.068476 sec, rd 1.648289 sec)
benched 16.00 GiB worth of memory (585.14 MiB/s) in 27.234011 secs total
```

### i7-4790K
```
discovered Intel(R) Core(TM) i7-4790K CPU @ 4.00GHz: 8 logical CPU(s), 4 physical, 2 thread(s) per core
measuring memory perf across CPU(s) with explicit memory mappings
running 32 trial(s) on a space of 128.00 MiB with 4 thread(s) per trial run
trial 32 of 32 [%100.00] (wr 1.405175 sec, rd 1.188535 sec)
thread averages:
  1 (wr 0.704807 sec, rd 0.703132 sec)
  2 (wr 0.549705 sec, rd 0.409998 sec)
  3 (wr 0.292535 sec, rd 0.232334 sec)
  4 (wr 0.156884 sec, rd 0.004112 sec)
total average: (wr 6.815728 sec, rd 5.398306 sec)
benched 16.00 GiB worth of memory (180.04 MiB/s) in 90.216036 secs total
```

### i7-6700k
```
discovered Intel(R) Core(TM) i7-6700K CPU @ 4.00GHz: 8 logical CPU(s), 4 physical, 2 thread(s) per core
measuring memory perf across CPU(s) with explicit memory mappings
running 32 trial(s) on a space of 128.00 MiB with 4 thread(s) per trial run
trial 32 of 32 [%100.00] (wr 1.415474 sec, rd 1.096290 sec)
thread averages:
  1 (wr 0.211443 sec, rd 0.188549 sec)
  2 (wr 0.163605 sec, rd 0.136219 sec)
  3 (wr 0.109080 sec, rd 0.078811 sec)
  4 (wr 0.051359 sec, rd 0.023321 sec)
total average: (wr 2.141946 sec, rd 1.707605 sec)
benched 16.00 GiB worth of memory (585.14 MiB/s) in 27.065301 secs total
```

### Ryzen 1700
```
discovered AMD Ryzen 7 1700 Eight-Core Processor: 16 logical CPU(s), 8 physical, 2 thread(s) per core
measuring memory perf across CPU(s) with explicit memory mappings
running 32 trial(s) on a space of 128.00 MiB with 8 thread(s) per trial run
trial 32 of 32 [%100.00] (wr 3.409272 sec, rd 3.044805 sec)
thread averages:
  1 (wr 0.376523 sec, rd 0.358443 sec)
  2 (wr 0.329873 sec, rd 0.306196 sec)
  3 (wr 0.283812 sec, rd 0.261372 sec)
  4 (wr 0.235190 sec, rd 0.210351 sec)
  5 (wr 0.183385 sec, rd 0.159213 sec)
  6 (wr 0.132993 sec, rd 0.112440 sec)
  7 (wr 0.084588 sec, rd 0.063350 sec)
  8 (wr 0.038941 sec, rd 0.016044 sec)
total average: (wr 13.322433 sec, rd 11.899265 sec)
benched 32.00 GiB worth of memory (337.81 MiB/s) in 96.391158 secs total
```
