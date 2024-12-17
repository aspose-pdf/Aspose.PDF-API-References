---
title: "Grayscale"
second_title: Aspose.PDF for Go via C++
description: "Convert PDF-document to black and white."
type: docs
url: /go-cpp/organize/grayscale/
---

_Convert PDF-document to black and white._

```go
func (document *Document) Grayscale() error
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
	// Grayscale() converts PDF-document to black and white
	err = pdf.Grayscale()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) saves previously opened PDF-document with new filename
	err = pdf.SaveAs("sample_Grayscale.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf.Close()
}
```
