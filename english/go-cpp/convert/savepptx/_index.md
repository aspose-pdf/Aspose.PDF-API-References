---
title: "SavePptX"
second_title: Aspose.PDF for Go via C++
description: "Convert and save the previously opened PDF-document as PptX-document."
type: docs
url: /go-cpp/convert/savepptx/
---

_Convert and save the previously opened PDF-document as PptX-document._

```go
func (document *Document) SavePptX(filename string) error
```

**Parameters**: 
  * **filename** - new filename

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
	// SavePptX(filename string) saves previously opened PDF-document as PptX-document with filename
	err = pdf.SavePptX("sample.pptx")
	if err != nil {
		log.Fatal(err)
	}
}
```
