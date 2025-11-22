---
title: "Open"
second_title: Aspose.PDF for Go via C++
description: "Open a PDF-document with filename."
type: docs
url: /go-cpp/core/open/
---

_Open a PDF-document with filename._

```go
func Open(filename string) (*Document, error)
```

**Parameters**: 
  * **\*Document** - pointer to document
  * **filename** - full file name of the PDF-document

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
	// Save() saves previously opened PDF-document
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
