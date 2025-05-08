IDIR=./includes
EXECUTABLES_DIR=./bin
SOURCE_CODE_DIR=./includes
COMPILER=nvcc
COMPILER_FLAGS=-I$(IDIR) -I/usr/local/cuda/include -lcuda --std c++17 -rdc=true -lcudadevrt

.PHONY: clean build run

$(EXECUTABLES_DIR):
    
	mkdir -p $(EXECUTABLES_DIR)

build: $(EXECUTABLES_DIR) $(SOURCE_CODE_DIR)/complex.cu
    
	$(COMPILER) $(COMPILER_FLAGS) -DNVCC_FAILS_HERE $(SOURCE_CODE_DIR)/complex.cu -o $(EXECUTABLES_DIR)/complex.exe

clean:
    
	rm -rf $(EXECUTABLES_DIR)/complex.exe

run:
    
	$(EXECUTABLES_DIR)/complex.exe

all: clean build run