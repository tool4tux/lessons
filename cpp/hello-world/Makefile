.phony: clean
APP=hello

$(APP): $(APP).o
	g++ $< -o $@ 

$(APP).o: $(APP).cpp
	g++ -c $< -o $@

clean:
	-rm -rf $(APP)
	-rm -rf *.o
