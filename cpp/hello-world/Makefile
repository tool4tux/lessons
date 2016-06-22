.phony: clean
APP=hello

all: $(APP)

$(APP): $(APP).o
	g++ $< -o $@ 

$(APP).o: $(APP).cpp
	g++ -c $< -o $@

clean:
	-rm -rf $(APP)
	-rm -rf *.o
