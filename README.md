# ebpf-checklist
Check list of eBPF or non-eBPF tools to performance analysis

![bcc-tracing](http://www.brendangregg.com/BPF/bcc_tracing_tools_early2019.png)
![ebpf_support](http://www.brendangregg.com/eBPF/linux_ebpf_support.png)

## Tools

- uprobres - user-space hooks
- kprobes - kernel-space hooks
- execsnoop - check what running on system
- opensnoop - print syscall to `open(2)`
- ext4slower - waiting for disk i/o
- tcpconnect - active TCP connection
- tcpaccept - idle TCP connection
- profile - print sumary of CPU usage
