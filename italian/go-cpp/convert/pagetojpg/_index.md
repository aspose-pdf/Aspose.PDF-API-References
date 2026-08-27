---
title: "PageToJpg"
second_title: "Aspose.PDF per Go via C++"
description: "Converti e salva la pagina specificata come Jpg-image."
type: docs
url: /it/go-cpp/convert/pagetojpg/
---

_Converti e salva la pagina specificata come immagine Jpg._

```go
func (document *Document) PageToJpg(num int32, resolution_dpi int32, filename string) error
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
	// PageToJpg(num int32, resolution_dpi int32, filename string) salva la pagina specificata come file immagine Jpg
	err = pdf.PageToJpg(1, 100, "sample_page1.jpg")
	if err != nil {
		log.Fatal(err)
	}
}
```
