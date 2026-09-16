# OperatingSystem
It will contain solutions for Operating System Problems

## PROCESS SYNCHRONIZATION
##Problem Statement 1: Producer Consumer Problem

The Producer-Consumer problem is a classic synchronization problem in operating systems where multiple processes or threads share a common buffer. Proper synchronization prevents race conditions and ensures correct access to the shared resource.
i) Producers insert data items into the shared buffer.
ii) Consumers remove and process data items from the shared buffer.

##Problem Statement 2: Reader Writer Problem

The Readers-Writers Problem is a classic synchronization issue in operating systems. It deals with coordinating access to shared data (e.g., database, file) by multiple processes or threads.
i) Readers: Multiple readers can read the shared data simultaneously without causing inconsistency (since they don’t modify data).
ii) Writers: Only one writer can access the data at a time, and no readers are allowed while writing (to prevent data corruption).

The challenge is to design a synchronization scheme that ensures:
i) Multiple readers can access data together if no writer is writing.
ii) Writers have exclusive access no other reader or writer can enter during writing.

##Problem Statement 3: Dining Philosophers Problem

The Dining Philosopher Problem involves 'n' philosophers sitting around a circular table. Each philosopher alternates between two states: thinking and eating. To eat, a philosopher needs two chopsticks, one on their left and one on their right. However, the number of chopsticks is equal to the number of philosophers, and each chopstick is shared between two neighboring philosophers.

The standard problem considers the value of 'n' as 5 i.e. we deal with 5 Philosophers sitting around a circular table.
