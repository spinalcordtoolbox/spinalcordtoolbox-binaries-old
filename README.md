# spinalcordtoolbox-binaries

* This repository was an empty repository that was only ever used to temporarily store the SCT binaries for Windows platforms.
* The name of this repository conflicts with the name of the repository used for building binaries via CI (https://github.com/kousu/spinalcordtoolbox-binaries). 
* So, the following steps were taken:
   * Fork https://github.com/kousu/spinalcordtoolbox-binaries under "spinalcordtoolbox-binaries-CI"
   * In the forked respository, create an identical release to store the Windows binaries.
   * Rename this repo from "spinalcordtoolbox-binaries" to "spinalcordtoolbox-binaries-old"
   * Rename ehe CI repo from "spinalcordtoolbox-binaries-CI" to "spinalcordtoolbox-binaries"
