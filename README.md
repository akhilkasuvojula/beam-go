# beam-go
## commands
go get -u github.com/apache/beam/sdks/v2/go/pkg/beam
go install github.com/apache/beam/sdks/v2/go/examples/wordcount
go run wordcount.go --input sample.txt --output kasuvojula.txt
go get github.com/apache/beam/sdks/v2/go/pkg/beam/io/filesystem/gcs@v2.37.0
go run wordcount.go --input sample.txt --output kasuvojula.txt
