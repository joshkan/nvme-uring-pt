# nvme-uring-pt

This contains the patches sent to LKML for uring-passthrough over nvme.

# How to use
**********
Step 1:

Clone the linux-block (for-next) branch as follows:
```
git clone https://git.kernel.dk/cgit/linux-block/log/?h=for-next

```
Step 2:

Checkout the following commit as follows:
```
git checkout cb690f5238d71f543f4ce874aa59237cf53a877c
```

Step 3:

Apply all the patches from the latest version.

# Changelog
## v6(latest)
What it contains
****************
- async passthrough polling support
- fixed-buffer support simplified (no need of new NVMe ioctl)


## v5
What it contains
****************
- async-passthrough over nvme per-namespace char device (/dev/ngXnY)
- fixed-buffer support over uring-passthrough

The base uring-passthrough support comes from the Jens kernel (refer below)



