all: sim

sim:
	g++ -std=c++14 -g -I./include src/main.cpp src/Core.cpp src/multiCore.cpp src/Memory.cpp src/PipelineRegister.cpp -o ./bin/sim

clean:
	rm -f bin/sim
