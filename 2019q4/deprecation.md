## Component Deprecation ##

Link:	 [Deprecation Plan](https://wiki.freebsd.org/DeprecationPlan)

Contact: Ed Maste <emaste@FreeBSD.org>  
Contact: Warner Losh <imp@FreeBSD.org>  

We plan to deprecate a number of components in advance of
FreeBSD 13.  As a result a number of user-facing notices were added to
man pages, program startup, or kernel messages.

Deprecated components that have been removed or have removal planned
include:

_Userland_
- GCC 4.2.1
- sranddev(3)
- amd(8) legacy automount daemon
- picobsd(8)
_Kernel_
- arm (v5) CPU architecture support
- random(9) 
- timeout(9)

If you have an interest in any of these components please follow up on the
FreeBSD-current mailing list.
