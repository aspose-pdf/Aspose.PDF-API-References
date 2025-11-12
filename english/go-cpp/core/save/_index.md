---
title: "Save"
second_title: Aspose.PDF for Go via C++
description: "Save the previously opened PDF-document."
type: docs
url: /go-cpp/core/save/
---

_Save the previously opened PDF-document._

```go
func (document *Document) Save() error
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
	// Close() releases allocated resources for PDF-document
	defer pdf.Close()
	// Save() saves previously opened PDF-document
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
