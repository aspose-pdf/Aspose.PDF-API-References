---
title: "RemovePdfaCompliance"
second_title: Aspose.PDF for Go via C++
description: "Remove PDF/A compliance from a PDF-document."
type: docs
url: /go-cpp/organize/removepdfacompliance/
---

_Remove PDF/A compliance from a PDF-document._

```go
func (document *Document) RemovePdfaCompliance() error
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
	// RemovePdfaCompliance() removes PDF/A compliance from PDF-document
	err = pdf.RemovePdfaCompliance()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) saves previously opened PDF-document with new filename
	err = pdf.SaveAs("sample_RemovePdfaCompliance.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
