# Makefile for main src
export CXX = g++
export CXXFLAGS = -Wall -O2 -std=c++11
all:
	$(MAKE) -C streams/
	$(MAKE) -C structs/
	$(MAKE) -C stack/

clean:
	$(MAKE) -C streams/ clean
	$(MAKE) -C structs/ clean
	$(MAKE) -C stack/ clean
