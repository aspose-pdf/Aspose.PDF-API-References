---
title: "WordCount"
second_title: Aspose.PDF for Go via C++
description: "Return word count in PDF-document."
type: docs
url: /go-cpp/core/wordcount/
---

_Return word count in PDF-document._

```go
func (document *Document) WordCount() (int32, error)
```

**Parameters**: 

**Return**: 
  * **int32** - word count of the PDF-document
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) opens a PDF-document with filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf.Close()
	// WordCount() returns word count in PDF-document
	word_count, err := pdf.WordCount()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Word count:", word_count)
}
```
