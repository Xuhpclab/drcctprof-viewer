# DrCCTProf Viewer README

DrCCTProf Viewer is an extension atop Vscode.
DrCCTProf Viewer can show multiple interactive views for users to go through the profiling data collecte by various tools. Moreover, it supports an easy way to corelate profiling results with program source codes.
Currently, DrCCTProf Viewer supports two formats of profiling data: [pprof format](https://github.com/google/pprof/blob/master/proto/profile.proto) and [drcctprof format](https://github.com/Xuhpclab/DrCCTProf). Thus, DrCCTProf Viewer can directly open profiling files produced by pprof and DrCCTProf.


## Usage


### Open DrCCTProf Viewer

There are three typical ways to open a file in pprof/DrCCTProf formats.

> **Tips:**
*For go pprof output files, you need to unzip them first.*

#### 1. Open DrCCTProf Viewer from Vscode Explorer View

(1) Right-click the profile file.

(2) Click "show DrCCTProf Viewer".

![open1](https://raw.githubusercontent.com/Xuhpclab/drcctprof-viewer/main/res/open1.gif)

#### 2. Open DrCCTProf Viewer from Vscode Editor View

(1) Click the profile file to open it with editor view.

(2) Click the "show DrCCTProf Viewer" button in the top right of the editor view.

![open2](https://raw.githubusercontent.com/Xuhpclab/drcctprof-viewer/main/res/open2.gif)

#### 3. Make DrCCTProf Viewer as the default view by changing the file extension suffix

(1) Add an extension suffix (***.drcctprof***) to the unzipped profile file.

(2) Click the file to open the view of DrCCTProf Viewer.

![open3](https://raw.githubusercontent.com/Xuhpclab/drcctprof-viewer/main/res/open3.gif)

### Use case

#### A demo to explore DrCCTProf Viewer

![demo](https://raw.githubusercontent.com/Xuhpclab/drcctprof-viewer/main/res/demo.gif)
