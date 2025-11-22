---
title: "Close"
second_title: Aspose.PDF for Go via C++
description: "Release allocated resources for PDF-document."
type: docs
url: /go-cpp/core/close/
---

_Release allocated resources for PDF-document._

```go
func (document *Document) Close() error
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
