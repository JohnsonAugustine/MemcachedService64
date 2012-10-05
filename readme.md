Wrapper for memcached 64 bits
=========================

Usable as a service and console program (for diagnostics).

Parameters are passed to memcached through the configuration file (app.config).

Logs and console output are managed with NLog (NLog.config).

Service install / uninstall
------------------------
MemcachedService64.exe --install

MemcachedService64.exe --uninstall

Memcached options
------------------------
http://hpux.connect.org.uk/hppd/hpux/Misc/memcached-1.4.5/man.html

Based on version 1.4.5
------------------------
* binary:
http://downloads.northscale.com/memcached-1.4.5-amd64.zip
* found through:
http://blog.elijaa.org/index.php?post/2010/08/25/Memcached-1.4.5-for-Windows

See also
--------
* http://memcached.org/
* http://code.google.com/p/memcached/
