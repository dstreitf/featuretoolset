# install tools

git
g++-Compiler - Version 5.4.0
cppcheck
make
dot (graphviz)
evince - Viewer for ps-files
pkg-config

# compile

g++ -std=c++11 -I . main.cpp feature.cpp dependency.cpp analyzer.cpp utils/log.cpp dependencies/mandatory.cpp dependencies/optional.cpp dependencies/or.cpp dependencies/xor.cpp -o main

# execute

./main 
