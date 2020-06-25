.PHONY: node-deps deps validate

node-deps:
	npm install -g @apidevtools/swagger-cli

deps: node-deps

validate:
	swagger-cli validate api.yaml

release: validate
