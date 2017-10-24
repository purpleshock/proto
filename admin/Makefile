services = register.pb.go

.PHONY: clean all

all: $(services)

$(services): %.pb.go: %.proto
	protoc --go_out=. $<
