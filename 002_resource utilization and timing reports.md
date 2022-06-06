### Resource utilization report
Find the kernel_util_routed.rpt file
> find . -name kernel_util_routed.rpt  
> ![avatar](./pictures/002/find_kernel_util_routed_rpt.png)  

The detailed report is as follow:
> ![avatar](./pictures/002/kernel_util_routed_rpt.png)

### Timing report
Find the timing report file
> find . -name *bb_locked_timing_summary_routed.rpt
> ![avatar](./pictures/002/find_timingrpt.png)

The detailed report is as follow:
> ![avatar](./pictures/002/timing_report.png)

### Accelerator execution time
original host.cpp
![avatar](./pictures/002/host_cpp0.png)

modified host.cpp
![avatar](./pictures/002/host_cpp1.png)

execution result
![avatar](./pictures/002/execution_results.png)

### Summary
|||
|---------|----------------|
|Time     |0.00010536 sec  |
|GOPS     |1.30447e+06     |
|LUT      |7317            |
|LUTAsMem |1173            |  
|REG      |16350           | 
|BRAM     |23              |
|URAM     |0               |
|DSP      |0               |
|WNS      |0.022           |  
