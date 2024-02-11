# Homework Assignment 1

Submission Deadline: February 12, 2024

Ioannis Rodosthenous 

#### Latency (us)

Through my measurements, it was found that local DRAM exhibits the lowest latency at merely 0.0981 us. It was also determined that the latency for Rack DRAM is less than that of Rack Disk. These figures were obtained by adding network latency to local disk and DRAM latencies, respectively, to derive the latencies for Rack Disk and Rack DRAM.

#### Capacity (GB)

Observing two identical nodes, it's noted that both share equal storage capacities, with their DRAM at 164.91 GB and local disk storage at 1100 GB.

#### Bandwidth (MB/s)

Examining the bandwidth, a significant figure is observed for Local DRAM bandwidth, amounting to 55000 MB/s, which is substantially higher than others. The disk bandwidth, measured using the "fio" command, stands at 386.034 MB/s. For calculating the Rack DRAM bandwidth, essentially the network bandwidth, the "iperf" command was utilized to identify the network bottleneck, which was found to be 725.76 MB/s.

### Conclusion

In summary, accessing remote DRAMs is found to be much more efficient and easier compared to local disks, attributed to the significantly higher bandwidths facilitated by the network serving as the bottleneck.


![Results-EPL452-HW1](https://github.com/ucy-cs452-sp24/hw1-irodos01/assets/81627543/3f995f55-7f6f-44ca-920a-24921c103d4a)
