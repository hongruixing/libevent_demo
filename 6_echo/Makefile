echo: echo.cpp
	g++ $^ -o $@ -levent -std=c++11 -lpthread
	@echo "---------------------app start------------------------"
	./$@
clean:
	rm -rf test_server
	rm -rf *.o
