# Producer-Consumer-with-Semaphores
Semaphore Solution to Producer Consumer Problem
Program starts with 100 empty slots and 0 full slots.  The producer takes 1 from
the empty  slots and adds 1 to the full slots only if there is an empty, otherwise,
it waits.  The consumer takes from the full slots and adds to the empty slots; if
there are no full slots, the consumer waits.  The producer and consumer are
each run ten times in the program as forked processes.
