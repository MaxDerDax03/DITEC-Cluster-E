# Technical references – checked links for the technical track

For all teams · status 13.09.2026 · all links checked on 13.09.2026 (HTTP status in brackets)

**Course weeks:**
- **W2** bootcamp, 23.09
- **W3** SLAM and Nav2, 30.09
- **W5** dynamic environments, 14.10
- **W6** mission logic and IT integration, 21.10
- **W7** benchmark, 26.–28.10

**Rule:** always use the **Jazzy** version of a page. Many search results point to Humble or Rolling pages, or to old URLs.

---

## Robot and ROS 2 basics

| Resource | Link | Status | Use it for … | Weeks |
|---|---|---|---|---|
| TurtleBot 4 User Manual | https://turtlebot.github.io/turtlebot4-user-manual/ | OK; Jazzy is listed in the manual | Robot setup, networking, sensors, Create 3 base | W2, W3, W6 |
| – TB4 simulator (Gazebo) | https://turtlebot.github.io/turtlebot4-user-manual/software/turtlebot4_simulator.html | OK | Starting the simulated TB4 | W2 |
| – Generating a map | https://turtlebot.github.io/turtlebot4-user-manual/tutorials/generate_map.html | OK | First SLAM map with the TB4 launch files | W3 |
| – TurtleBot 4 Navigator | https://turtlebot.github.io/turtlebot4-user-manual/tutorials/turtlebot4_navigator.html | OK | Python API for goals, waypoints and docking | W3, W6 |
| ROS 2 Jazzy tutorials | https://docs.ros.org/en/jazzy/Tutorials.html | OK | Official tutorial index | W2 |
| – Beginner: CLI tools | https://docs.ros.org/en/jazzy/Tutorials/Beginner-CLI-Tools.html | OK | Nodes, topics, services, parameters, launch, bags | W2 |
| – Beginner: client libraries | https://docs.ros.org/en/jazzy/Tutorials/Beginner-Client-Libraries.html | OK | Packages, publishers and subscribers in Python | W2 |
| iRobot Create 3 docs | https://iroboteducation.github.io/create3_docs/ | OK; Jazzy support for the firmware **not verified** on these pages | Base firmware, docking station, hazard and bumper topics | W2, W6 |
| TurtleBot 4 source code | https://github.com/turtlebot/turtlebot4 | OK; `jazzy` branch exists | Reading launch files and configs | W3 |

## Mapping and navigation

| Resource | Link | Status | Use it for … | Weeks |
|---|---|---|---|---|
| Nav2 documentation (Jazzy) | https://docs.nav2.org/jazzy/ | OK | Entry point | W3–W7 |
| – Navigation concepts | https://docs.nav2.org/jazzy/getting_started/navigation_concepts/ | OK | Servers, costmaps, TF, state estimation, behaviour trees | W3 |
| – First-time robot setup guide | https://docs.nav2.org/jazzy/configuration_and_development/first_time_robot_setup_guide/ | OK | Footprint, odometry, sensors, Gazebo | W3 |
| – Tuning guide | https://docs.nav2.org/jazzy/configuration_and_development/tuning_guide/ | OK | Inflation, footprint, controller and planner choice | W3, W5, W7 |
| – Behaviour trees | https://docs.nav2.org/jazzy/getting_started/nav2_behavior_trees/ | OK | Default BTs, recovery behaviour, custom BT nodes | W5, W6 |
| – Collision Monitor | https://docs.nav2.org/jazzy/configuration_and_development/configuration_guide/core_servers/collision_monitor/ | OK | Stop and slow-down zones around people | W5 |
| – Docking server (configuration) | https://docs.nav2.org/jazzy/configuration_and_development/configuration_guide/core_servers/configuring_docking_server/ | OK | Parameters for the docking server | W6 |
| – Using docking (tutorial) | https://docs.nav2.org/jazzy/tutorials/general_tutorials/using_docking/ | OK | Dock and undock as part of the mission | W6 |
| slam_toolbox | https://github.com/SteveMacenski/slam_toolbox | OK; `jazzy` branch exists | Mapping modes, map serialisation, localisation mode | W3 |

**Note on Nav2 URLs:** older links such as `docs.nav2.org/concepts/index.html`, `/tuning/index.html` and `/behavior_trees/index.html` now return **404**. The documentation was restructured, so use the paths above.

## Simulation and people

| Resource | Link | Status | Use it for … | Weeks |
|---|---|---|---|---|
| Gazebo Harmonic docs | https://gazebosim.org/docs/harmonic/getstarted/ | OK | Installing Gazebo, SDF worlds, GUI | W2 |
| – ROS 2 integration | https://gazebosim.org/docs/harmonic/ros2_integration/ | OK | Bridging topics between Gazebo and ROS 2 | W2 |
| – Actors | https://gazebosim.org/docs/harmonic/actors/ | OK | Scripted walking people (simplest pedestrian option) | W5 |
| ros_gz | https://github.com/gazebosim/ros_gz | OK; `jazzy` branch exists | Bridge, spawning models, message types | W2, W5 |
| HuNavSim (jazzy fork) | https://github.com/voshch/hunav_sim | OK; `jazzy` branch exists (see caveat below) | Pedestrians driven by the social force model, which react to the robot | W5, W7 |
| HuNavSim upstream | https://github.com/robotics-upo/hunav_sim | not checked in a browser; the repository has `humble`, `foxy` and `v2.0` branches but **no `jazzy` branch** | Original project, papers, metrics | W7 |
| Arena-Rosnav (reference only) | https://github.com/Arena-Rosnav | OK | Lecturer demo, world ideas, metric definitions | W7 |

**HuNavSim caveat:** the README on the `jazzy` branch of the voshch fork still says "Tested in ROS2 Humble" and "V2.0 is under development". Test it early, in W3, and keep scripted Gazebo actors as a fallback.

## Mission logic, IT integration and security

| Resource | Link | Status | Use it for … | Weeks |
|---|---|---|---|---|
| BehaviorTree.CPP | https://www.behaviortree.dev/ · https://github.com/BehaviorTree/BehaviorTree.CPP | OK | The BT library inside Nav2; XML trees, Groot2 | W6 |
| py_trees | https://py-trees.readthedocs.io/en/devel/ | OK | Python behaviour trees for order → pick-up → deliver → dock | W6 |
| py_trees_ros | https://github.com/splintered-reality/py_trees_ros | OK | ROS 2 bindings for py_trees | W6 |
| SROS2 tutorial (Jazzy) | https://docs.ros.org/en/jazzy/Tutorials/Advanced/Security/Introducing-ros2-security.html | OK | Keystores, enclaves, encrypted DDS | W6 |
| SROS2 repository | https://github.com/ros2/sros2 | OK | Tools and examples | W6 |

## Safety standard

**ISO 13482:2014** – *Robots and robotic devices – Safety requirements for personal care robots*
- Link: https://www.iso.org/standard/53820.html
- Status: blocked (HTTP 403 to automated checks). The page exists according to search results; open it in a browser.
- **What it covers:** safety requirements (inherently safe design, protective measures, information for use) for non-medical personal care robots. The three types are the mobile servant robot, the physical assistant robot and the person carrier.
- A café delivery robot is closest to the "mobile servant robot". The full text is paywalled; the ISO page shows the scope.
- **Revision:** ISO/FDIS 13482, *Robotics – Safety requirements for service robots*, https://www.iso.org/standard/83498.html, will replace the 2014 edition and extends the scope to professional and commercial service robots.
  - Secondary sources (iTeh Standards catalogue; Intertek webinar 2026) mention an effective date of 12.02.2026, and new clauses on cyber-security and on robots using lifts.
  - Publication status on iso.org: **not verified**.
- Use it for the W6 safety rules and W7 requirements (speed near people, stop distances). It is mandatory reading before real-robot tests.

## Free video courses and tutorials for ROS 2 beginners

| Resource | Link | Status | Use it for … | Weeks |
|---|---|---|---|---|
| The Construct Robotics Institute – "Learn ROS2 Jazzy Crash Course 2025" (YouTube) | https://www.youtube.com/watch?v=Se5pvRlTX8s | OK (video exists) | One-sitting refresher before the bootcamp | W2 |
| Automatic Addison – "Jazzy – Beginners – ROS 2 Fundamentals" (YouTube playlist) | https://www.youtube.com/playlist?list=PLNWNEEf8BvG64FVZT4IdieI1PuYnHkUrt | OK (playlist exists) | Step-by-step Jazzy basics | W2 |
| Articulated Robotics – "Getting Ready to Build Robots with ROS!" (YouTube playlist) | https://www.youtube.com/playlist?list=PLunhqkrRNRhYYCaSTVP-qJnyUPkTxJnBt | OK; the ROS 2 distro used in the videos is **not verified** (likely older than Jazzy) | Concepts: Linux, URDF, TF, packages | W2, W3 |
| Josh Newans – robotics_resources (curated list) | https://github.com/joshnewans/robotics_resources | OK | Finding further material | any |
