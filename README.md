# PART and PERFX

##### About

These are two tools that I wrote a long time ago, and were generally useful. However, I have not tested them much nor have I used them recently. So they may be useful to you, but you will want to carefully evaluate their performance.

 - [PART](http://www.mccauslandcenter.sc.edu/crnl/tools/part) is a Physiological Artifact Removal Tool for MRI scans
 - [Perfx](http://www.mccauslandcenter.sc.edu/crnl/tools/pwi) is a perfusion estimation tool.

##### Recent Versions

14 Feb 2015
 - Initial Github releases

##### Installation and Compiling

You can build these tools from the command line, assuming you have [Lazarus](http://www.lazarus-ide.org) installed.

```
lazbuild -B part.lpr
lazbuild -B perfx.lpr
```

With MacOS, lazbuild will compile as a 32-bit executable. For very large datasets you may want to explicitly compile the software as a 64-bit executable:

```
lazbuild --cpu=x86_64 -B part.lpr
lazbuild --cpu=x86_64 -B perfx.lpr

```

##### License

These toolsare released under the [BSD license](https://opensource.org/licenses/BSD-2-Clause)


