---
title: "Dynamic Sequence Reordering for Truck Platooning"
collection: publications
category: conferences
permalink: /publication/2025-11-12-dynamic-sequence-reordering-for-truck-platooning
excerpt: '트럭 군집주행을 위한 동적 순서 재배치 — a CARLA/ROS2 implementation of two intra-platooning position-change maneuvers (cyclic reorder and tail-to-lead promotion) built on camera-based multi-lane detection and 2D-lidar gap sensing.'
date: 2025-11-12
venue: 'Korean Society of Automotive Engineers (KSAE), Autumn Conference'
paperurl: '/files/dynamic-sequence-reordering-for-truck-platooning.pdf'
citation: 'Yoonjin Cho, Daeho Won, Jeongyun Choi, Jong-Chan Kim. (2025). &quot;Dynamic Sequence Reordering for Truck Platooning.&quot; <i>The Korean Society of Automotive Engineers, Autumn Conference</i>. 744.'
---

Platooning lets several vehicles travel at a fixed gap to improve fuel economy and traffic efficiency, but situations such as a lead-vehicle swap, energy management, or a fault response require safely changing a vehicle's position within the platoon &mdash; an intra-platooning position-change maneuver.

This work implements two such maneuvers in CARLA (ROS2, Town04_Opt map): a cyclic full-platoon reorder, and a tail-vehicle-to-lead promotion. Camera images are converted to a bird's-eye view and processed with a sliding-window technique for multi-lane detection, while a 2D lidar's point cloud is used to maintain inter-vehicle distance. Each maneuver is implemented as an explicit state machine (lane change &rarr; gap control &rarr; merge &rarr; re-sequence) to keep the position exchange safe and repeatable.

[Download paper here](/files/dynamic-sequence-reordering-for-truck-platooning.pdf)
