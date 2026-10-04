---
title: "Range-Efficiency Assessment Method for Dynamic e-Truck Platoon"
collection: publications
category: conferences
permalink: /publication/2026-range-efficiency-assessment-method-for-dynamic-e-truck-platoon
excerpt: '전기 트럭 군집주행 대열 최적화를 위한 주행 효율성 평가 방법 — a CARLA + ROS Bridge + Python-BMS evaluation framework that scores dynamic position-change strategies in electric truck platoons on energy efficiency, SoC uniformity, and scenario execution time.'
date: 2026-01-01
venue: 'Korean Society of Automotive Engineers (KSAE)'
paperurl: '/files/range-efficiency-assessment-method-for-dynamic-e-truck-platoon.pdf'
citation: 'Yoonjin Cho, Daeho Won, Jeongyun Choi, Jong-Chan Kim. (2026). &quot;Range-Efficiency Assessment Method for Dynamic e-Truck Platoon.&quot; <i>Korean Society of Automotive Engineers (KSAE)</i>.'
---

In an electric truck platoon, the lead vehicle absorbs most of the aerodynamic drag and drains its battery (SoC) far faster than the following vehicles &mdash; so the platoon's range ends up bottlenecked by the lead truck even while trailing trucks still have charge left. Comparing dynamic position-change strategies meant to fix this imbalance has lacked a standardized way to measure whether they actually help.

This paper proposes an evaluation framework built on the CARLA simulator, ROS Bridge, and a Python-based Battery Management System, benchmarking three driving modes &mdash; fixed order (Lane Keeping), full reorder (Auto Reorder), and tail-to-lead promotion (Auto Promote Tail) &mdash; against four metrics: average fleet energy efficiency, SoC uniformity across trucks, scenario execution time, and critical driving distance (distance travelled before any truck's SoC first drops to 50%). Across the two reordering strategies, SoC standard deviation at the threshold point dropped by roughly 26&ndash;37&times; versus the fixed-order baseline, and platoon range extended by up to about 5.6%. Outstanding Presentation Paper Award (Poster Division).

[Download paper here](/files/range-efficiency-assessment-method-for-dynamic-e-truck-platoon.pdf)
