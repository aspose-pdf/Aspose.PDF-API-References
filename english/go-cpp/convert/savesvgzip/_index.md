---
title: "SaveSvgZip"
second_title: Aspose.PDF for Go via C++
description: "Convert and save the previously opened PDF-document as SVG-archive."
type: docs
url: /go-cpp/convert/savesvgzip/
---

_Convert and save the previously opened PDF-document as SVG-archive._

```go
func (document *Document) SaveSvgZip(filename string) error
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
	// SaveSvgZip(filename string) saves previously opened PDF-document as SVG-archive with filename
	err = pdf.SaveSvgZip("sample_svg.zip")
	if err != nil {
		log.Fatal(err)
	}
}
```
