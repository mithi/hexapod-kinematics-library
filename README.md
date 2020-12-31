[![npm](https://img.shields.io/npm/v/hexapod-kinematics-library.svg)](https://www.npmjs.com/package/hexapod-kinematics-library)
[![minified](https://img.shields.io/bundlephobia/min/hexapod-kinematics-library?color=%2300BCD4&label=minified)](https://bundlephobia.com/result?p=hexapod-kinematics-library)
[![gzipped size](https://img.shields.io/bundlephobia/minzip/hexapod-kinematics-library?color=%2300BCD4&label=minified%20%2B%20gzipped)](https://bundlephobia.com/result?p=hexapod-kinematics-library)
[![install size](https://packagephobia.now.sh/badge?p=hexapod-kinematics-library)](https://packagephobia.com/result?p=hexapod-kinematics-library)
[![code climate](https://codeclimate.com/github/mithi/hexapod-kinematics-library/badges/gpa.svg)](https://codeclimate.com/github/mithi/hexapod-kinematics-library)
[![technical debt](https://img.shields.io/codeclimate/tech-debt/mithi/hexapod-kinematics-library)](https://codeclimate.com/github/mithi/hexapod-kinematics-library/trends/technical_debt)
[![code coverage](https://codecov.io/gh/mithi/hexapod-kinematics-library/branch/main/graph/badge.svg?token=JW0Z2IOSRX)](https://codecov.io/gh/mithi/hexapod-kinematics-library)
![Main Passing](https://github.com/mithi/hexapod-kinematics-library/workflows/main/badge.svg)
[![buy me coffee](https://img.shields.io/badge/Buy%20me%20-coffee!-orange.svg?logo=buy-me-a-coffee&color=795548)](https://ko-fi.com/minimithi)

# Hexapod Kinematics Library

<p align="center">
    <img src="https://mithi.github.io/robotics-blog/show-off-v2-4.gif" alt="drawing" width="400" />
</p>

Code you can use to solve forward/inverse kinematics and generate walk sequences of hexapod robots. The codebase is largely copied from [Mithi's Bare Minimum Hexapod Robot Simulator 2](https://github.com/mithi/hexapod). [![Commit snapshot](https://img.shields.io/badge/commit%20snapshot-467d1a3b9-orange.svg?color=purple)](https://github.com/mithi/hexapod/tree/467d1a3b92dabd0304c7ef4675d64179f82efb69/src/hexapod)

Docs are written in the files themselves:

-   [`VirtualHexapod`](./src/VirtualHexapod.js)
-   [`getWalkSequence`](./src/solvers/walkSequenceSolver.js)
-   [`solveInverseKinematics`](./src/solvers/ik/hexapodSolver.js)

You can also inspect the [test directory](https://github.com/mithi/hexapod-kinematics-library/tree/main/tests) to see examples of how to use.

## Contributing [![PRs welcome!](https://img.shields.io/badge/PRs-welcome-orange.svg?style=flat)](https://github.com/mithi/mithi/wiki/Contributing)

Please read the [contributing guidelines](https://github.com/mithi/mithi/wiki/Contributing) and the recommended [commit style guide](https://github.com/mithi/mithi/wiki/Commit-style-guide)! Thanks!
