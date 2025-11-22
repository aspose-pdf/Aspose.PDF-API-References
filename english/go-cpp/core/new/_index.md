---
title: "New"
second_title: Aspose.PDF for Go via C++
description: "Create a new PDF-document."
type: docs
url: /go-cpp/core/new/
---

_Create a new PDF-document._

```go
func New() (*Document, error)
```

**Parameters**: 

**Return**:
  * **\*Document** - pointer to document
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// New creates a new PDF-document
	pdf, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf.Close()
	// SaveAs(filename string) saves previously opened PDF-document with new filename
	err = pdf.SaveAs("sample_New_SaveAs.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
