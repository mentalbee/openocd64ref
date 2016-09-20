# openocd64ref
OpenOCD patch to enable 64 bit operation. This code is for reference only. Consider it to be completely untested.
To apply the patch, use the base of the changes: 1ea25b85bb8ad4b4ccde1b8bff0cffe24bbb2f97
```
   git://git.code.sf.net/p/openocd/code openocd-public
   cd openocd-public
   git checkout -b mycontributions 1ea25b85bb8ad4b4ccde1b8bff0cffe24bbb2f97
   git am ../openocd-git-2.patch
```
