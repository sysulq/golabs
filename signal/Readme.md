Signal
======

* Use os.Interrupt to catch signal 2, and syscall.SIGTERM to catch signal 15, we can achieve gracefully shutdown in this way.
* Cannot catch signal 9, which is generated by kill -9.