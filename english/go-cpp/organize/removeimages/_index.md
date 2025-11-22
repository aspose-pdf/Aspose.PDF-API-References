---
title: "RemoveImages"
second_title: Aspose.PDF for Go via C++
description: "Remove images from PDF-document."
type: docs
url: /go-cpp/organize/removeimages/
---

_Remove images from PDF-document._

```go
func (document *Document) RemoveImages() error
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
	// RemoveImages() removes images from PDF-document
	err = pdf.RemoveImages()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) saves previously opened PDF-document with new filename
	err = pdf.SaveAs("sample_RemoveImages.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
