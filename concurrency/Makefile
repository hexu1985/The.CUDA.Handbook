APPS=nullKernelAsync

all: ${APPS}

%: %.cu
#	nvcc -O2 -arch=sm_20 -o $@ $<
	nvcc -I../chLib -O2 -o $@ $<
clean:
	rm -f ${APPS}
