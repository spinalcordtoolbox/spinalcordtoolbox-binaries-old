# spinalcordtoolbox-binaries

This repository used to be an empty repository that was only ever used to [temporarily store the SCT binaries for Windows platforms(https://github.com/spinalcordtoolbox/spinalcordtoolbox-binaries-old/releases/tag/test-release).

However, the name of this repository ("spinalcordtoolbox-binaries") conflicted with the name of the repository that is used for building binaries via CI: https://github.com/kousu/spinalcordtoolbox-binaries

So, the following steps were taken:
   * Fork https://github.com/kousu/spinalcordtoolbox-binaries under "spinalcordtoolbox-binaries-CI"
   * In the forked respository, create an [identical release](https://github.com/spinalcordtoolbox/spinalcordtoolbox-binaries/releases/tag/test-release) to match the [old, existing release](https://github.com/spinalcordtoolbox/spinalcordtoolbox-binaries-old/releases/tag/test-release).
   * Rename this repo from "spinalcordtoolbox-binaries" to "spinalcordtoolbox-binaries-old" and archive it.
   * Rename ehe CI repo from "spinalcordtoolbox-binaries-CI" to "spinalcordtoolbox-binaries"
