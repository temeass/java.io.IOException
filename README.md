java.io.IOException
===================

 Insufficient as (address space) or memlock
    
    java.io.IOError: java.io.IOException: Map failed  at 
    
 Insufficient memlock settings

    WARN [main ] 2011-06-15 09:58:56,861 CLibrary.java  (line 118) Unable to lock JVM memory  (ENOMEM).
    This can result in part of the JVM being swapped out, especially with mmapped I/O enabled.
    Increase RLIMIT_MEMLOCK or run <server_apps> as root.

