.PHONY: all clean help

all: .build

.build: package.json Makefile
	npm install

clean:
	rm -rf ./node_modules 

help:
	@echo 'Usage: make [all|clean]'
	@echo 'Options:'
	@echo '    all        Default]Build all apps'
	@echo '    clean      Cleanup all apps'