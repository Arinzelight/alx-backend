# 0x01. Caching

## Learning Objectives

### General

- **What a caching system is:** 
  A caching system is a mechanism used to store frequently accessed data in a temporary storage area called cache. This helps in speeding up data retrieval and improving overall system performance.

- **What FIFO means:** 
  FIFO stands for First In, First Out. In the context of caching, it means that the first item added to the cache will be the first one to be removed when the cache reaches its maximum capacity.

- **What LIFO means:** 
  LIFO stands for Last In, First Out. It's the opposite of FIFO, where the last item added to the cache will be the first one to be removed when the cache is full.

- **What LRU means:** 
  LRU stands for Least Recently Used. In this caching strategy, the least recently accessed items are removed from the cache when it's full.

- **What MRU means:** 
  MRU stands for Most Recently Used. In this strategy, the most recently accessed items are retained in the cache while the older ones are evicted when the cache is full.

- **What LFU means:** 
  LFU stands for Least Frequently Used. In this caching approach, the least frequently accessed items are removed from the cache when it's full.

- **What the purpose of a caching system is:** 
  The purpose of a caching system is to improve performance and efficiency by reducing the time and resources required to access frequently used data. By storing frequently accessed data closer to the user or application, caching minimizes the need to retrieve the data from slower, distant sources.

- **What limits a caching system has:** 
  Caching systems have limitations such as:
  - Limited storage capacity: Caches can only store a finite amount of data, and when the cache is full, it needs to evict some items to make room for new ones.
  - Cache eviction policies: Deciding which items to remove from the cache when it's full can be challenging and can impact the effectiveness of the caching system.
  - Cache coherence: Ensuring that the data in the cache is up-to-date and consistent with the source data can be a challenge, especially in distributed systems.


