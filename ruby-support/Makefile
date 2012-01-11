OUTPUT_DIR=output
DIA2CODE=../dia2code/dia2code
DIA_FILE=./test.dia
all:
	make test && make doc
test:
	if [ ! -d ${OUTPUT_DIR} ]; then \
		mkdir ${OUTPUT_DIR}; fi
	${DIA2CODE} ${DIA_FILE} -d ${OUTPUT_DIR}
doc:
	rdoc -o ${OUTPUT_DIR}/docs
clean:
	rm -Rf ${OUTPUT_DIR}
