1. Clone
   git clone --recurse-submodules https://github.com/wenhaocs/ProjectExample.git
2. Build dependency
   ./build-dependency.sh
3. Build
cmake -DCMAKE_BUILD_TYPE=Release ..
make
