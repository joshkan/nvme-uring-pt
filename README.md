# nvme-uring-pt

This contains the patches sent to LKML for uring-passthrough over nvme.

#v5
What it contains
****************
5th revision of patchset containing: 
- async-passthrough over nvme per-namespace char device (/dev/ngXnY)
- fixed-buffer support over uring-passthrough

The base uring-passthrough support comes from the Jens kernel (refer below)

How to use
**********

Step 1:
Clone the source/branch from -
https://git.kernel.dk/cgit/linux-block/log/?h=io_uring-fops.v5

Step 2:
Apply patches 1 to 6.


