---
layout: post
title: glitch update 2 
---
This is just a really basic update to the project that adds a winform GUI to allow selection of a psd file and application of the glitch process.  Output is simply pushed to the application directory.  The process button can be hit repeatedly, so multiple different runs can be done on the same file without re-selecting the file.  Future updates should include more configuration parameters and the potential for a "save as" function (though because the process is random, it might be easier to just specify a single output directory and have everything go there).  The output file naming convention might change in the future as well (because using a prefix means output ordering isn't necessarily the simplest to navigate).

Basic screenshot of the user interface:

![glitch gui](/img/interface.jpg)

As an experiment, I created an installation package using the default visual studio publish capability.  The glitch gui bundle can be downloaded here: [Glitch.zip](/file/Glitch.zip).  This should work as a standard windows program install/uninstall.  Provided without warranty or support, use at your own risk.
