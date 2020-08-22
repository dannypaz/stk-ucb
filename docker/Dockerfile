FROM i386/debian:latest
RUN apt-get update -y
RUN apt-get install wget alien libsm6 libx11-6:i386 -y
RUN wget http://inst.eecs.berkeley.edu/~scheme/precompiled/Linux/STk-4.0.1-ucb1.3.6.i386.rpm && \
	alien -i STk-4.0.1-ucb1.3.6.i386.rpm
CMD stk-simply
