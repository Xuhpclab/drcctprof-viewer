# DrCCTProf Viewer README

DrCCTProf Viewer can show interactive views for users to go through the profiling data. In addition, it also provides users an easy way to jump from the profiling result to source code.
Now DrCCTProf Viewer can open two Protocol buffers formats data: [pprof format](https://github.com/google/pprof/blob/master/proto/profile.proto) and [drcctprof format](https://github.com/Xuhpclab/DrCCTProf).


## Usage


### Open DrCCTProf Viewer

There are three ways for users to open pprof format or drcctprof format data.

> **Tips:**
*For go pprof output files, you need to unzip them first.*

#### Open DrCCTProf Viewer from Vscode Explorer View

1. right-click the profiling output file.

2. click "show DrCCTProf Viewer."

![open1](https://raw.githubusercontent.com/Xuhpclab/drcctprof-viewer/main/res/open1.gif)

#### Open DrCCTProf Viewer from Vscode Editor View

1. click the profiling output file open it with editor view.

2. click the "show DrCCTProf Viewer" button in the top right of the editor view.

![open2](https://raw.githubusercontent.com/Xuhpclab/drcctprof-viewer/main/res/open2.gif)

#### Make DrCCTProf Viewer as default view by changing the file suffix

1. Add a suffix (***.drcctprof***) to the unzipped file

2. click the file to open the DrCCTProf Viewer view.

![open3](https://raw.githubusercontent.com/Xuhpclab/drcctprof-viewer/main/res/open3.gif)

### Use case

#### Gif Demo

![demo](https://raw.githubusercontent.com/Xuhpclab/drcctprof-viewer/main/res/demo.gif)