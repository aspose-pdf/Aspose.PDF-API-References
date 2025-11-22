---
title: "Optimize"
second_title: Aspose.PDF for Go via C++
description: "Optimize PDF-document content."
type: docs
url: /go-cpp/organize/optimize/
---

_Optimize PDF-document content._

```go
func (document *Document) Optimize() error
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
	// Optimize() optimizes PDF-document content
	err = pdf.Optimize()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) saves previously opened PDF-document with new filename
	err = pdf.SaveAs("sample_Optimize.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
