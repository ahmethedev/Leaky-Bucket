# Leaky Bucket Algorithm for Congestion control.

This is one of the algorithm used for congestion control in network layer. 
Leaky Bucket:
Each host is connected to the network by an interface containing a leaky bucket, that is, a finite internal queue. If a packet arrives at the queue when it is full, the packet is discarded. In other words, if one or more process are already queued, the new packet is unceremoniously discarded. This arrangement can be built into the hardware interface or simulate d by the host operating system. In fact it is nothing other than a single server queuing system with constant service time.

# How to test 

1. Download the code (git clone)
2. Compile the file (gcc -o main main.c)
3. Run the code (./main)

# Resouces:
The links I've used for that code: https://fsmk-vtu-cs-department-lab-manual-for-c-programming.readthedocs.io/en/latest/VTU/Sem7/Networks_Lab/12LeakyBucket/LeakyBucket/