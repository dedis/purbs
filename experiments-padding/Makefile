python_scripts=$(shell ls *.py)

py:
	for f in $(python_scripts) ; do \
		echo "Running ./$$f"; \
        python3 ./$$f ; \
    done

.PHONY: clean
clean:
	rm -rf *.eps

.PHONY: all
all: clean py