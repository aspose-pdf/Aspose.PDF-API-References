---
title: "PageRemoveTables"
second_title: Aspose.PDF for Go via C++
description: "Remove tables in page."
type: docs
url: /go-cpp/organize/pageremovetables/
---

_Remove tables in page._

```go
func (document *Document) PageRemoveTables(num int32) error
```

**Parameters**: 
  * **num** - page number of the PDF-document

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
	// PageRemoveTables(num int32) removes tables in page
	err = pdf.PageRemoveTables(1)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) saves previously opened PDF-document with new filename
	err = pdf.SaveAs("sample_page1_RemoveTables.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf.Close()
}
```
