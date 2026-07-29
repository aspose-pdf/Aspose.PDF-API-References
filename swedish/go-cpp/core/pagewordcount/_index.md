---
title: "PageWordCount"
second_title: "Aspose.PDF för Go via C++"
description: "Returnera ordantal på angiven sida i PDF-dokument."
type: docs
url: /sv/go-cpp/core/pagewordcount/
---

_Returnera antalet ord på angiven sida i PDF-dokumentet._

```go
func (document *Document) PageWordCount(num int32) (int32, error)
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **int32** - word count on the page
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
	// PageWordCount(num int32) returnerar antalet ord på angiven sida i PDF-dokumentet.
	page_word_count, err := pdf.PageWordCount(1)
	if err != nil {
		log.Fatal(err)
	}
	// Skriv ut
	fmt.Println("Word count on the first page:", page_word_count)
}
```
