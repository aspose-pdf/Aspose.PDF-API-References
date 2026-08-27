---
title: "PageGrayscale"
second_title: "Aspose.PDF para Go vía C++"
description: "Convertir la página a blanco y negro."
type: docs
url: /es/go-cpp/organize/pagegrayscale/
---

_Convertir página a blanco y negro._

```go
func (document *Document) PageGrayscale(num int32) error
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) abre un PDF-documento con el nombre de archivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// PageGrayscale(num int32) convierte la página a blanco y negro
	err = pdf.PageGrayscale(1)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_page1_Grayscale.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
