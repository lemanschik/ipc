# ipc
Understand the B8G Engine IPC Internals

b8g offers out of the box a lot of context implementations with multiple security implications the most generic one is a general context we call that
isolate a isolate can get passed to a c function as arrgument to get used this implements the concepts of capn where we create sharedMemory as wire layout but we do not use the capn implementation for that we would only use capn in complex legacy interop scenarios which we today not got. 

but in theory  it could produce the best possible links to existing legacy software like capn-http from cloudflare.
