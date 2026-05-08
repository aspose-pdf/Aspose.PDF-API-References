---
title: "RemovePdfUaCompliance"
second_title: Aspose.PDF for Go via C++
description: "Remove PDF/UA compliance from a PDF-document."
type: docs
url: /go-cpp/organize/removepdfuacompliance/
---

_Remove PDF/UA compliance from a PDF-document._

```go
func (document *Document) RemovePdfUaCompliance() error
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
	// RemovePdfUaCompliance() removes PDF/UA compliance from PDF-document
	err = pdf.RemovePdfUaCompliance()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) saves previously opened PDF-document with new filename
	err = pdf.SaveAs("sample_RemovePdfUaCompliance.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
