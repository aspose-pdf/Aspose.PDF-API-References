---
title: "SplitAtPage"
second_title: Aspose.PDF for Go via C++
description: "Split the PDF-document into two new PDF-documents."
type: docs
url: /go-cpp/core/splitatpage/
---

_Split the PDF-document into two new PDF-documents._

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
	// Open(filename string) opens a PDF-document with filename
	pdf_split, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf_split.Close()

	// SplitAtPage(document *Document, page int) creates two new PDF-documents
	left, right, err := asposepdf.SplitAtPage(pdf_split, 2)
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for resulting PDF-documents
	defer left.Close()
	defer right.Close()

	// Save each part as a separate file
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
