# Sam Doane

I build tools for robot learning and the software around it. I'm a robotics researcher at USC's Dynamic Robotics and Control Laboratory, studying mechanical engineering and pursuing an M.S. in Artificial Intelligence and Machine Learning.

My work spans reinforcement learning, MuJoCo simulation, motion retargeting, and the tools needed to inspect experiments and evaluate what a policy actually learned.

[Portfolio](https://www.samueldoaneportfolio.com) · [LinkedIn](https://www.linkedin.com/in/samdoane/)

## Selected work

| Project | What to explore |
| --- | --- |
| [RL-Sculptor](https://github.com/sjdoane/RL-Sculptor) | A Python/FastAPI/React platform for generating and revising RL rewards from simulation rollouts, with research retrieval and checks on generated metrics. [Demo](https://www.loom.com/share/f13cda84b42b406ca48c8ceea2c36e17). |
| [Humanoid Harness](https://github.com/sjdoane/humanoid-harness) | Research on revising reference guidance and task rewards for humanoid post-training. The public repository documents its development proxy, experiments, and integration limits. |
| [PIT Backtest](https://github.com/sjdoane/pit-backtest) | A point-in-time equity research framework with leakage checks, explicit cost assumptions, and reproducible figures. |
| [Pendulum Drag Extraction](https://github.com/sjdoane/pendulum-drag-extraction) | A team experiment estimating drag from pendulum decay, with MATLAB analysis, apparatus details, figures, and the report. |

## Open source

Merged upstream contributions:

| Project | Change |
| --- | --- |
| [Minari](https://github.com/Farama-Foundation/Minari) (Farama Foundation) | Offline-RL dataset integrity, both shipped in [v0.6.0](https://github.com/Farama-Foundation/Minari/releases/tag/v0.6.0): combining datasets now [rejects incompatible observation and action spaces](https://github.com/Farama-Foundation/Minari/pull/373) instead of saving the wrong space metadata, and splitting [rejects negative sizes](https://github.com/Farama-Foundation/Minari/pull/374) that put one episode in two partitions. |
| [trimesh](https://github.com/mikedh/trimesh) | Plane slicing [reuses vertices that lie on the cutting plane](https://github.com/mikedh/trimesh/pull/2661), so capped slices of watertight meshes stay closed (merged for the next release). Camera copies [keep their clipping planes and intrinsics](https://github.com/mikedh/trimesh/pull/2643) (released in 5.2.1). |
| [PyRoboPlan](https://github.com/sea-bass/pyroboplan) | [Fixes inverse-kinematics target aliasing and Cartesian planning state](https://github.com/sea-bass/pyroboplan/pull/129): the solver no longer overwrites a target pose borrowed from its own kinematics data, which could report a false success. |
| [Viser](https://github.com/viser-project/viser) | [Browser regression test](https://github.com/viser-project/viser/pull/791) for a skinned-mesh cleanup crash, merged with the maintainer's broader lifecycle fix. |

I also reported a [state-mutation bug in pymoo's KKTPM metric](https://github.com/the-dual-space/pymoo/issues/814), which the maintainer reproduced and fixed.

**Tools I work with:** Python, C++, TypeScript, PyTorch, MuJoCo/MJX, JAX, React, FastAPI, MATLAB, and CAD.

I'm interested in robot learning, simulation, and practical tools that make experiments easier to reproduce and understand.
