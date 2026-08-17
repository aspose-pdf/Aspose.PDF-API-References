---
title: "ReorderPages"
second_title: Aspose.PDF for Go via C++
description: "Reorder pages in PDF-document."
type: docs
url: /go-cpp/organize/reorderpages/
---

_Reorder pages in PDF-document._

```go
func (document *Document) ReorderPages(numPages ...int) error
```

**Parameters**: 
  * **numPages** - a slice of new page positions (1-based); the pages you list are placed first in the given order, and all unlisted pages keep their original order and follow them

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) opens a PDF-document with filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf.Close()

	// ReorderPages() reorders pages in PDF-document
	err = pdf.ReorderPages(2, 1)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) saves previously opened PDF-document with new filename
	err = pdf.SaveAs("sample_ReorderPages.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
