SRCS  := $(wildcard *.c)
TARGET := $(SRCS:.c=)
LFLAG := -L ../lib -lrbtree
CFLAG := -I ../include

all : ${TARGET} 

%:%.c
	gcc  $^ ${LFLAG} ${CFLAG} -o $@

clean:
		rm ${TARGET}
