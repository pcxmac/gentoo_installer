# gentoo_installer
a python set of scripts for live or boot-to-live environment for installing gentoo on BTRFS, ZFS, and other file systems. Utilizes YAML configurations and has unit-tests. BASH is only used as a brief interface, if python cannot address effeciently enough. 

Can create a bottable USB for boot-to-live environment.

supports custom initramfs for protected rootfs/user space

includes : (separate github projects) { python + eBPF }

  update-agent (for working on BTRFS/ZFS/COW F-S) to perform silent / background updates, and boot loader updates as well as initramfs-updates AND kernel updates.
  
  kernel-view (visualization of the kernel, for more intuitive module implementation)
  
  adaptive-fw (firewall which can, under limited scope, adapt to networking changes / daemon)
  
  logging-facility (collection of several logging facilities, kernel_panics, kernel messages, syslog messages, init messages, w/ backup online/offline schema)
  
  gentoo-info (package information + gentoo OS configuration information)
