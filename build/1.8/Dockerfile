FROM golang:1.8

# Install govendor
RUN go get -u github.com/kardianos/govendor

ADD compile.sh /tmp/compile.sh
CMD /tmp/compile.sh