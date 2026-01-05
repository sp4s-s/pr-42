## Project Description
--------------------------------
### Panic Pr-42

- Checkpoints 
- Copy on write
- Memory zero latency
- Clock Synchronization
- Time Rollback
- Failure time stamp correct [ PnL , Audits]


- Thread Stall
- DB/DS Mid Transaction Write
- Lock free Ds + Journaling + Write Ahead Logging


## 1st Draft
```hand-craft
OOM, DeadLocks, rewinding system using snapshots [recovery], restore-sys backup wo data corruption, lock-free ds, crash consistent in-memory ds, 

Isolating bad tasks, mem-faults, latency spikes, partial data corruption

Checkpoints [low latency]
copy-on-write, memory mapped files, near zero latency hit

Clock Synchronization
Clock Drift, Time Rollback, Failure time stamp correction [PnL, Audits]

Thread stalls , DB/DS - Mid-Transaction/Mid-Write Recovery

```

