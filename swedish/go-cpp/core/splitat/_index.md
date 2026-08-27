---
title: "SplitAt"
second_title: "Aspose.PDF för Go via C++"
description: "Dela det aktuella PDF-dokumentet i två nya PDF-dokument."
type: docs
url: /sv/go-cpp/core/splitat/
---

_Dela det aktuella PDF-dokumentet i två nya PDF-dokument._

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
	// Open(filename string) öppnar ett PDF-dokument med filnamn
	pdf_split, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() frigör allokerade resurser för PDF-dokument
	defer pdf_split.Close()

	// SplitAt(page int) delar det aktuella PDF-dokumentet i två nya PDF-dokument.
	left, right, err := pdf_split.SplitAt(2)
	if err != nil {
		log.Fatal(err)
	}
	// Close() frigör allokerade resurser för de resulterande PDF-dokumenten
	defer left.Close()
	defer right.Close()

	// Spara varje del som en separat fil
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
