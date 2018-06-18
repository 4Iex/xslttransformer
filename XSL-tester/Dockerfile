FROM hseeberger/scala-sbt
RUN mkdir /XSL-tester
COPY . /XSL-tester
RUN cd /XSL-tester
RUN ls /XSL-tester
RUN apt-get update
RUN sbt
RUN sbt package
RUN sbt play run
