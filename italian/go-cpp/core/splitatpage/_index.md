---
title: "SplitAtPage"
second_title: "Aspose.PDF per Go via C++"
description: "Dividi il documento PDF in due nuovi documenti PDF."
type: docs
url: /it/go-cpp/core/splitatpage/
---

_Dividi il PDF-document in due nuovi PDF-documents._

```go
func SplitAtPage(document *Document, page int) (*Document, *Document, error)
```

**Parameters**: 
  * **document** - pointer to document
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

	// SplitAtPage(document *Document, page int) crea due nuovi PDF-documents
	left, right, err := asposepdf.SplitAtPage(pdf_split, 2)
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per i documenti PDF risultanti
	defer left.Close()
	defer right.Close()

	// Salva ogni parte come file separato
	err = left.SaveAs("sample_SplitAtPage_left.pdf")
	if err != nil {
		log.Fatal(err)
	}
	err = right.SaveAs("sample_SplitAtPage_right.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
