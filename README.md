# SE3082 - Parallel Computing: Lab 10

## Exercise 1(b) — Launch Configuration Benchmarking

| Lab 9 Program | Launch Configuration | Run 1 (s) | Run 2 (s) | Run 3 (s) |
| :--- | :--- | :--- | :--- | :--- |
| **Exercise 3** | 512 blocks × 1 thread | 0.0000989 | 0.0001040 | 0.0001211 |
| **Exercise 4** | 1 block × 512 threads | 0.0001011 | 0.0001719 | 0.0001090 |
| **Exercise 5** | 10,000,000 elements, 19,532 blocks × 512 threads | 0.0006289 | 0.0006311 | 0.0006311 |
| **Exercise 6** | 100,000,000 elements, 313 × 625 blocks of 32 × 16 | 0.0048130 | 0.0047910 | 0.0047870 |
