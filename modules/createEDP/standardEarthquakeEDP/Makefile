include ../../Makefile.inc

all: StandardEarthquakeEDP 

StandardEarthquakeEDP.o : StandardEarthquakeEDP.cpp

StandardEarthquakeEDP: StandardEarthquakeEDP.o
	$(CXX) $(LDFLAGS) -o StandardEQEDP StandardEarthquakeEDP.o $(LDLIBS)

clean:
	$(RM) *.o *~

distclean: clean
	$(RM) StandardEQEDP 


