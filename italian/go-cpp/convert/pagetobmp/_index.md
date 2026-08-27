---
title: "PageToBmp"
second_title: "Aspose.PDF per Go via C++"
description: "Converti e salva la pagina specificata come Bmp-image."
type: docs
url: /it/go-cpp/convert/pagetobmp/
---

_Converti e salva la pagina specificata come Bmp-image._

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
	// Open(filename string) apre un PDF-document con filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer pdf.Close()
	// PageToBmp(num int32, resolution_dpi int32, filename string) salva la pagina specificata come file Bmp-image
	err = pdf.PageToBmp(1, 100, "sample_page1.bmp")
	if err != nil {
		log.Fatal(err)
	}
}
```
