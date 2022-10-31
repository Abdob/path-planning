```
cd /opt/carla-simulator/
SDL_VIDEODRIVER=offscreen ./CarlaUE4.sh -opengl
```
```
git clone git@github.com:Abdob/path-planning.git

cd path-planning/project
./install-ubuntu.sh
cd starter_files/
cmake .
sudo apt-get install libgtest-dev
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
