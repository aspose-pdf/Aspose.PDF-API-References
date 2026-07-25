---
title: "PageToPdf"
second_title: "Aspose.PDF per Go via C++"
description: "Converti e salva la pagina specificata come Pdf."
type: docs
url: /it/go-cpp/convert/pagetopdf/
---

_Converti e salva la pagina specificata come Pdf._

```go
func (document *Document) PageToPdf(num int32, filename string) error
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
	// Open(filename string) apre un PDF-document con filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer pdf.Close()
	// PageToPdf(num int32, filename string) salva la pagina specificata come file Pdf
	err = pdf.PageToPdf(1, "sample_page1.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
