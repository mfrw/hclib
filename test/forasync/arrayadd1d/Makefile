include $(HCLIB_ROOT)/include/hclib.mak

EXE=arrayadd1d

all: clean $(EXE) clean-obj

arrayadd1d: arrayadd1d.cpp
	$(CXX) $(PROJECT_CXXFLAGS) $(PROJECT_LDFLAGS) -o $@ $^ $(PROJECT_LDLIBS)

clean-obj:
	rm -rf *.o *.dSYM

clean:
	rm -rf *.o $(EXE) *.dSYM
