export CXX = g++
export CXXFLAGS = -Wall -O2 -std=c++11

all: test_stack

test_stack: ../src/stack/stack.o

test: all
	./test_stack

clean:
	$(MAKE) -C ../src/stack/ clean

cleaner: clean
	rm -f ./test_stack
