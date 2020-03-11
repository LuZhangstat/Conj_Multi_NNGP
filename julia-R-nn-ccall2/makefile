
all:
	g++ -c -fpic nn.cpp -o nn.o
	g++ -shared -o nn.so nn.o
	mkdir -p ../sim/pics
	mkdir -p ../sim/sim1/results
	mkdir -p ../RDA/pics
	mkdir -p ../RDA/data/conj_data
	mkdir -p ../RDA/data/LMC_data
	mkdir -p ../RDA/results/conj
	mkdir -p ../RDA/results/misalign_resp	

clean:
	rm *.o *.so
