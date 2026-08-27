---
title: "WordCount"
second_title: "Aspose.PDF för Go via C++"
description: "Returnera antalet ord i PDF-dokumentet."
type: docs
url: /sv/go-cpp/core/wordcount/
---

_Returnera ordantal i PDF-dokument._

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
	// Open(filename string) öppnar ett PDF-dokument med filnamn
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() frigör allokerade resurser för PDF-dokument
	defer pdf.Close()
	// WordCount() returnerar ordantal i PDF-dokument
	word_count, err := pdf.WordCount()
	if err != nil {
		log.Fatal(err)
	}
	// Skriv ut
	fmt.Println("Word count:", word_count)
}
```
