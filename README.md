# RootInBinder
Testing using root in binder for the CMS OD workshop

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/katilp/RootInBinder/master)

Contains an example output file.
A different output file can be uploaded to the mybinder workspace.

The first start of the notebook can be slow because of the build, but should be faster when a build exists.

To do:
- figure out how to display the contents of a RDataFrame
- add some basic plotting
- add some basic cuts
- estimate the max size of the file which can reasonably be uploaded
- for the example file:
   - the output.root is 10000 evts/2.7 MB from AOD2NanoAODOutreachTool
   - runtime as [a github workflow](https://github.com/katilp/AOD2NanoAODOutreachTool/actions/runs/139672160) (including container build) was 15 mins without condition data access
   - time that locally (with a previously downloaded container)
