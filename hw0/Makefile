# NOTE: on MacOS you need to add an addition flag: -undefined dynamic_lookup
default:
	c++ -O3 -Wall -shared -std=c++11 -fPIC $$(python3 -m pybind11 --includes) -undefined dynamic_lookup -I/Library/Developer/CommandLineTools/Library/Frameworks/Python3.framework/Versions/3.9/include/python3.9 src/simple_ml_ext.cpp -o src/simple_ml_ext.so

