```
cd /opt/carla-simulator/
SDL_VIDEODRIVER=offscreen ./CarlaUE4.sh -opengl
```
```
git clone https://github.com/udacity/nd013-c5-planning-starter.git
cd nd013-c5-planning-starter/project
./install-ubuntu.sh
cd starter_files/
cmake .
make
cd nd013-c5-planning-starter/project
./run_main.sh
// This will silently fail 
ctrl + C to stop 
./run_main.sh again
Go to desktop mode to see CARLA
```

```
// If error bind is already in use, or address already being used
ps -aux | grep carla
kill id
```
