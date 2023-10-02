# shfs

Sync Hash File System - allows syncing between devices and storing large files as references keyed by the file hash.

Mount on linux:

`mount -o port=<n>,mountport=<n>,nfsvers=3,noacl,tcp -t nfs localhost:/mount <mountpoint>`
