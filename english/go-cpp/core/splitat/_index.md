---
title: "SplitAt"
second_title: Aspose.PDF for Go via C++
description: "Split the current PDF-document into two new PDF-documents."
type: docs
url: /go-cpp/core/splitat/
---

_Split the current PDF-document into two new PDF-documents._

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
	// Open(filename string) opens a PDF-document with filename
	pdf_split, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf_split.Close()

	// SplitAt(page int) splits the current PDF-document into two new PDF-documents.
	left, right, err := pdf_split.SplitAt(2)
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for resulting PDF-documents
	defer left.Close()
	defer right.Close()

	// Save each part as a separate file
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
