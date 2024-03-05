 //all : test 
.PHONY: test  
obj = cos.o sin.o square_root.o tan.o
test : $(obj) main.cpp
	g++ $(obj) main.cpp -o calculator
	./calculator
%.o : scientific/%.cpp 
	g++ -c -o $@ $<
.PHONY : clean
clean:  
	rm *.o calculator

