# Portable Version of mrt_cmake_modules

## Usage
- Put this folder into your catkin workspace's src folder
- Move the CMakeLists.txt into the catkin workspace's src folder
- Remove build and devel folder if workspace was build before.
- Build with catkin_make (catkin build) does not work yet.

## FAQ
- You might need to install g++-4.9
```bash
sudo add-apt-repository ppa:ubuntu-toolchain-r/test
sudo apt-get update
sudo apt-get install build-essential
sudo apt-get install gcc-4.9 g++-4.9
sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-4.9 60 --slave /usr/bin/g++ g++ /usr/bin/g++-4.9 
```
