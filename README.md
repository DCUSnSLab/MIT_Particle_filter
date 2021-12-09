# MIT Particle filter

map server 설치

```bash
sudo apt-get update
rosdep install -r --from-paths src --ignore-src --rosdistro (ROS 버전) -y
```

RangeLibc 설치
```bash
sudo pip install cython
git clone http://itgit.cu.ac.kr/AutonomousDriving/range_libc-for-Noetic
cd range_libc-for-Noetic/pywrapper
# on VM
./compile.sh
# on car - compiles GPU ray casting methods
./compile_with_cuda.sh
```
이동 후 README에 따라 설치 진행

원 Github 주소 : https://github.com/mit-racecar/particle_filter
