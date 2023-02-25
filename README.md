# srvx-1.4.1-rc1-easy-scripting-
srvx 1.4.1-rc1 (easy-scripting)
install
aclocal
autoconf
autoreconf -f -i -Wall,no-obsolete
./configure  --enable-modules=hostserv,memoserv,watchdog,sockcheck,helpserv --enable-debug
