---
title: "SaveXlsX"
second_title: Aspose.PDF for Go via C++
description: "Convert and save the previously opened PDF-document as XlsX-document."
type: docs
url: /go-cpp/convert/savexlsx/
---

_Convert and save the previously opened PDF-document as XlsX-document._

```go
func (document *Document) SaveXlsX(filename string) error
```

**Parameters**: 

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
	// SaveXlsX(filename string) saves previously opened PDF-document as XlsX-document with filename
	err = pdf.SaveXlsX("sample.xlsx")
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf.Close()
}
```
