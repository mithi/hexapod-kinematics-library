[![NPM](https://img.shields.io/npm/v/hexapod-kinematics-library.svg)](https://www.npmjs.com/package/hexapod-kinematics-library)
[![MINIFIED](https://img.shields.io/bundlephobia/min/hexapod-kinematics-library?color=%2300BCD4&label=minified)](https://bundlephobia.com/result?p=hexapod-kinematics-library)
[![GZIPPED](https://img.shields.io/bundlephobia/minzip/hexapod-kinematics-library?color=%2300BCD4&label=minified%20%2B%20gzipped)](https://bundlephobia.com/result?p=hexapod-kinematics-library)
[![Install Size](https://packagephobia.now.sh/badge?p=hexapod-kinematics-library)](https://packagephobia.com/result?p=hexapod-kinematics-library)
[![Code Climate](https://codeclimate.com/github/mithi/hexapod-kinematics-library/badges/gpa.svg)](https://codeclimate.com/github/mithi/hexapod-kinematics-library)
[![technical debt](https://img.shields.io/codeclimate/tech-debt/mithi/hexapod-kinematics-library)](https://codeclimate.com/github/mithi/hexapod-kinematics-library/trends/technical_debt)
[![codecov](https://codecov.io/gh/mithi/hexapod-kinematics-library/branch/main/graph/badge.svg?token=JW0Z2IOSRX)](https://codecov.io/gh/mithi/hexapod-kinematics-library)
[![buy me coffee](https://img.shields.io/badge/Buy%20me%20-coffee!-orange.svg?logo=buy-me-a-coffee&color=795548)](https://ko-fi.com/minimithi)

# Hexapod Kinematics Library

<p align="center">
    <img src="https://mithi.github.io/robotics-blog/show-off.gif" alt="drawing" width="400" />
</p>

Code you can use to solve forward and inverse kinematics, generate walk sequences of hexapod robots as copied from [Mithi's Bare Minimum Hexapod Robot Simulator 2](https://github.com/mithi/hexapod). [commit: 467d1a3b9](https://github.com/mithi/hexapod/commit/467d1a3b92dabd0304c7ef4675d64179f82efb69)

Docs are written in the files themselves:

-   [`VirtualHexapod`](./src/VirtualHexapod.js)
-   [`getWalkSequence`](./src/solvers/walkSequenceSolver.js)
-   [`solveInverseKinematics`](./src/solvers/ik/hexapodSolver.js)

You can also inspect the [test directory](https://github.com/mithi/hexapod-kinematics-library/tree/main/tests) to see examples of how they're used.
