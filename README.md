# RootInBinder
Testing using root in binder for the CMS OD workshop

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/katilp/RootInBinder/master)

Contains an example output file.
A different output file can be uploaded to the mybinder workspace by clicking on the "Upload" button as shown in this figure

![File view](images/binder-add-file.png?raw=true "Adding files")

The first start of the notebook can be slow because of the build, but should be faster when a build exists.

The notebooks shows:
- how to open a file from a portal or a local file
- how to display some contents of the file
- how to see the variable names in the file
- how to do some basic plotting
- how to add some basic cuts

The example file:
   - the output.root is 10000 evts/2.7 MB from AOD2NanoAODOutreachTool
   - runtime as [a github workflow](https://github.com/katilp/AOD2NanoAODOutreachTool/actions/runs/139672160) (including container build) was 15 mins without condition data access
   - time that locally (with a previously downloaded container)
