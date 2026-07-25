---
title: "PageCount"
second_title: "Aspose.PDF per Go via C++"
description: "Restituisci il conteggio delle pagine nel documento PDF."
type: docs
url: /it/go-cpp/core/pagecount/
---

_Restituisce il conteggio delle pagine nel PDF-document._

```go
func (document *Document) PageCount() (int32, error)
```

**Parameters**: 

**Return**: 
  * **int32** - page count of the PDF-document
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) apre un PDF-document con filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer pdf.Close()
	// PageCount() restituisce il conteggio delle pagine nel PDF-document
	count, err := pdf.PageCount()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Count:", count)
}
```
