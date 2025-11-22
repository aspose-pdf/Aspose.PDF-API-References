---
title: "PageInsert"
second_title: Aspose.PDF for Go via C++
description: "Insert new page at the specified position in PDF-document."
type: docs
url: /go-cpp/core/pageinsert/
---

_Insert new page at the specified position in PDF-document._

```go
func (document *Document) PageInsert(num int32) error
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
	// Close() releases allocated resources for PDF-document
	defer pdf.Close()
	// PageInsert(num int32) inserts new page at the specified position in PDF-document
	err = pdf.PageInsert(1)
	if err != nil {
		log.Fatal(err)
	}
	// Save() saves previously opened PDF-document
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
