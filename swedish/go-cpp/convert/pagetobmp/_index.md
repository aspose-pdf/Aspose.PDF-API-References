---
title: "PageToBmp"
second_title: "Aspose.PDF för Go via C++"
description: "Konvertera och spara den angivna sidan som Bmp-bild."
type: docs
url: /sv/go-cpp/convert/pagetobmp/
---

_Konvertera och spara den angivna sidan som Bmp-bild._

```go
func (document *Document) PageToBmp(num int32, resolution_dpi int32, filename string) error
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
	// Open(filename string) öppnar ett PDF-dokument med filnamn
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() frigör allokerade resurser för PDF-dokument
	defer pdf.Close()
	// PageToBmp(num int32, resolution_dpi int32, filename string) sparar den angivna sidan som Bmp-bildfil
	err = pdf.PageToBmp(1, 100, "sample_page1.bmp")
	if err != nil {
		log.Fatal(err)
	}
}
```
