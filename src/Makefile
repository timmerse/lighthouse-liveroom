.PHONY: all clean dev prod help

all: .build

.build: package.json Makefile
	npm install && rm -f .build && touch .build

clean:
	rm -rf ./node_modules .build


help:
	@echo 'Usage: make [all|clean]'
	@echo 'Options:'
	@echo '    all        Default]Build all apps'
	@echo '    clean      Cleanup all apps'