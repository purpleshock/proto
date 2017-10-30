PROTO = *.proto
GO = *.pb.go

.PHONY: clean all

clean:
	$(RM) $(GO)

all: %.pb.go

%.pb.go:
	protoc --go_out=. $(wildcard $(PROTO))
