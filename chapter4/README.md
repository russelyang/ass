s -gstabs -o cpuid2-64.o cpuid2-64.s [ruyang@ubuntu:~/protest/ass/chapter4]$ld -lc -dynamic-linker /lib/x86_64-linux-gnu/ld-linux-x86-64.so.2 -o cpuid2-64 -lc  cpuid2-64.o
