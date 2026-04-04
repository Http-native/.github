## Welcome to Http-native foundation

Our goal is to speed up web development in every area, offering faster solutions that use less compute, follow modern developer standards the demands of the growing industry.

# Benchmark http-native vs bun vs express

Generated: 2026-04-01T13:47:31.363Z

Connections: 200
Duration: 10s
Timeout: 2s

| Engine | Scenario | RPS Mean | Latency Mean (ms) | Latency Max (ms) | Throughput (MB/s) |
| --- | --- | ---: | ---: | ---: | ---: |
| http-native | static | 111,175.00 | 1.80 | 22.36 | 16.95 |
| http-native | dynamic | 108,929.00 | 1.83 | 21.10 | 16.71 |
| http-native | opt | 65,648.14 | 3.04 | 22.11 | 11.39 |
| bun | static | 52,464.71 | 3.81 | 15.20 | 8.20 |
| bun | dynamic | 48,552.96 | 4.12 | 12.35 | 7.64 |
| bun | opt | 51,766.54 | 3.86 | 12.21 | 9.18 |
| express | static | 5,559.05 | 35.90 | 7,676.78 | 1.49 |
| express | dynamic | 5,621.90 | 35.51 | 7,106.52 | 1.51 |
| express | opt | 5,640.26 | 35.39 | 6,794.13 | 1.63 |
