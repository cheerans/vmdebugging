# vmdebugging

# to generate a heap dump, use this
jcmd 10888 GC.heap_dump ../dump.hprof 

use visual vm to connect to the host that is running jstatd

tools/plugins - install visual gc, jconsole plugins

jinfo pid - to get vm config info
