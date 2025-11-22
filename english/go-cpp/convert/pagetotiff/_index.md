---
title: "PageToTiff"
second_title: Aspose.PDF for Go via C++
description: "Convert and save the specified page as Tiff-image."
type: docs
url: /go-cpp/convert/pagetotiff/
---

_Convert and save the specified page as Tiff-image._

```go
func (document *Document) PageToTiff(num int32, resolution_dpi int32, filename string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **resolution_dpi** - resolution in DPI of the resulting file
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
	// PageToTiff(num int32, resolution_dpi int32, filename string) saves the specified page as Tiff-image file
	err = pdf.PageToTiff(1, 100, "sample_page1.tiff")
	if err != nil {
		log.Fatal(err)
	}
}
```
