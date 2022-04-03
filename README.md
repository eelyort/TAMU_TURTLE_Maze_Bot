# TAMU_TURTLE_Maze_Bot
## Project Setup
- https://docs.ros.org/en/galactic/Installation.html
- https://docs.ros.org/en/galactic/Tutorials/Configuring-ROS2-Environment.html
- Clone Repo
## Running/Compiling/Etc
### Setup
- Open "Developer Command Prompt for VS 2019"
  - OPEN AS ADMINISTRATOR
- cd repository root
  - should contain .gitignore, /build, /install, /log, /src
### Build
- Build project `colcon build --symlink-install`
  - Can run `colcon build --symlink-install --packages-select maze_bot` to only build our package other than the first time
- Call built setup: `call install\setup.bat`
### Run
- `ros2 run maze_bot NODE_NAME`
  - All node names can be found in /src/maze_bot/setup.py
