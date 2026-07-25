---
title: "SplitAt"
second_title: "Aspose.PDF per Go via C++"
description: "Dividi il documento PDF corrente in due nuovi documenti PDF."
type: docs
url: /it/go-cpp/core/splitat/
---

_Dividi il documento PDF corrente in due nuovi documenti PDF._

```go
func (document *Document) SplitAt(page int) (*Document, *Document, error)
```

**Parameters**: 
  * **page** - page number at which to split the PDF-document. Pages up to and including this page go into the first PDF-document

**Return**: 
  * **\*Document** - new PDF-document containing pages 1 to page (inclusive)
  * **\*Document** - new PDF-document containing pages from page + 1 to the end
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
	"github.com/aspose-pdf/aspose-pdf-go-cpp"
	"log"
)

func main() {
	// Open(filename string) apre un PDF-document con filename
	pdf_split, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer pdf_split.Close()

	// SplitAt(page int) divide il documento PDF corrente in due nuovi documenti PDF.
	left, right, err := pdf_split.SplitAt(2)
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per i documenti PDF risultanti
	defer left.Close()
	defer right.Close()

	// Salva ogni parte come file separato
	err = left.SaveAs("sample_SplitAt_left.pdf")
	if err != nil {
		log.Fatal(err)
	}
	err = right.SaveAs("sample_SplitAt_right.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
