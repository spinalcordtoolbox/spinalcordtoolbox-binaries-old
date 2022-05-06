# spinalcordtoolbox-binaries

This repository used to be an empty repository that was only ever used to [temporarily store the SCT binaries for Windows platforms](https://github.com/spinalcordtoolbox/spinalcordtoolbox-binaries-old/releases/tag/test-release).

However, the name of this repository ("spinalcordtoolbox-binaries") conflicted with the name of a new repository that was created for building binaries via CI: https://github.com/kousu/spinalcordtoolbox-binaries

To address the naming conflict, the following steps were taken:
   * Fork https://github.com/kousu/spinalcordtoolbox-binaries under "spinalcordtoolbox-binaries-CI"
   * In the forked respository, create an [identical release](https://github.com/spinalcordtoolbox/spinalcordtoolbox-binaries/releases/tag/test-release) in the new repo to match the [existing release](https://github.com/spinalcordtoolbox/spinalcordtoolbox-binaries-old/releases/tag/test-release) in the old repo.
   * Rename this repo from "spinalcordtoolbox-binaries" to "spinalcordtoolbox-binaries-old" and archive it.
   * Rename the new repo from "spinalcordtoolbox-binaries-CI" to "spinalcordtoolbox-binaries"
