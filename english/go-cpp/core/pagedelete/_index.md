---
title: "PageDelete"
second_title: Aspose.PDF for Go via C++
description: "Delete specified page in PDF-document."
type: docs
url: /go-cpp/core/pagedelete/
---

_Delete specified page in PDF-document._

```go
func (document *Document) PageDelete(num int32) error
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
	// PageDelete(num int32) deletes specified page in PDF-document
	err = pdf.PageDelete(1)
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
