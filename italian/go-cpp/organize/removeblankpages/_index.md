---
title: "Rimuovi pagine vuote"
second_title: "Aspose.PDF per Go via C++"
description: "Rimuovi le pagine vuote dal documento PDF."
type: docs
url: /it/go-cpp/organize/removeblankpages/
---

_Rimuovi pagine vuote da PDF-document._

```go
func (document *Document) RemoveBlankPages() error
```

**Parameters**: 

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) apre un PDF-document con filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer pdf.Close()
	// RemoveBlankPages() rimuove pagine vuote da PDF-document
	err = pdf.RemoveBlankPages()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) salva il PDF-document precedentemente aperto con un nuovo nome file
	err = pdf.SaveAs("sample_RemoveBlankPages.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
