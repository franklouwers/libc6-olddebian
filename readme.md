# Rebuilt libc6 packages for lenny (with "Ghost" patch)

We needed to build these packages to counter the Ghost issue.

## Why o why?

While it will be seen by some as a wrong thing to still have these systems
running, we can't migrate or upgrade these due to client restrictions.
And it's better to patch these, and help others by providing the work
we did to the community, as to be ashamed and keep this for ourselfs.

## What is there?

The binary packages are only provided as a help for those too lazy to 
build the packages themself. I made them by taking the source package,
unpackaging it, applying the Debian patches, and then applying the
same patch as the squeeze-lts team used to build their updated libc.
The patch applies nicely (with 1 HUNK) and package builds normally.


Cheers & happy ops'ing,

Openminds Ops Team
Ghostbuster Squad
