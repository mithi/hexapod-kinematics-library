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
