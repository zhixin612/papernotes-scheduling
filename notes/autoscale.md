## AutoScale: Dynamic, Robust Capacity Management for Multi-Tier Data Centers

### Abstract

We introduce a **dynamic capacity management policy**, AutoScale, that greatly **reduces the number of servers needed in data centers driven by unpredictable, time-varying load, while meeting response time SLAs.** AutoScale scales the data center capacity, adding or removing servers as needed.

### Problem

* The waste of resources in data centers is serious.
* Setup cost of servers and VMs makes dynamic capacity management difficult.
* Existing policy cannot meet time SLAs with high setup cost (turn the servers off too early).

### Existing research

* AlwaysOn
* Reactive; Reactive with extra capacity
* Predictive (sliding window); Predictive (linear regression)

### Key Points

* Delayed turn off

* Keep only a small number of servers in the idle state

  index-packing + join-the-shortest-queue routing

*  T=491ms, P=1297W, N=7.2

### Inspiration / Notes / Questions ...



