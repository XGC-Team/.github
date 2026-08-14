# XGC Team

XGC 做异构机器人集群的智能指控：地面站、编排内核、仿真与实机部署。

XGC builds command-and-control software for heterogeneous robot teams — ground station, orchestration, simulation, and field deployment.

## Public artifacts

| Repository | What it is |
| --- | --- |
| [`xgc2-images`](https://github.com/XGC-Team/xgc2-images) | Container images for simulation, development, CI, and deployment |

Images publish to GitHub Container Registry:

```text
ghcr.io/xgc-team/xgc2-images/<app>
```

Static catalog:

```text
https://raw.githubusercontent.com/XGC-Team/xgc2-images/master/catalog/index.yml
```

## Stack

ROS 1 / ROS 2 · PX4 SITL · Gazebo · QGroundControl · multi-arch (`amd64`, `arm64`)

More public repositories will land here as they are ready to publish.
