---
title: "PageToSvg"
second_title: Aspose.PDF for Go via C++
description: "Convert and save the specified page as Svg-image."
type: docs
url: /go-cpp/convert/pagetosvg/
---

_Convert and save the specified page as Svg-image._

```go
func (document *Document) PageToSvg(num int32, filename string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
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
	// PageToSvg(num int32, filename string) saves the specified page as Svg-image file
	err = pdf.PageToSvg(1, "sample_page1.svg")
	if err != nil {
		log.Fatal(err)
	}
}
```
