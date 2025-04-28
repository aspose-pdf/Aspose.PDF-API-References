---
title: "Append"
second_title: Aspose.PDF for Go via C++
description: "Append pages from another PDF-document."
type: docs
url: /go-cpp/core/append/
---

_Append pages from another PDF-document._

```go
func (document *Document) Append(anotherdocument *Document) error
```

**Parameters**: 
  * **filename** - new filename

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

	// Open(filename string) opens another PDF-document with filename
	anotherpdf, err := asposepdf.Open("sample1page.pdf")
	if err != nil {
		log.Fatal(err)
	}

	// Close() releases allocated resources for PDF-document
	defer anotherpdf.Close()

	// Append(anotherdocument *Document) appends pages from another PDF-document.
	err = pdf.Append(anotherpdf)
	if err != nil {
		log.Fatal(err)
	}

	// SaveAs(filename string) saves previously opened PDF-document with new filename
	err = pdf.SaveAs("sample_Append.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
