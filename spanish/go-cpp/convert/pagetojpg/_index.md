---
title: "PageToJpg"
second_title: "Aspose.PDF para Go vía C++"
description: "Convertir y guardar la página especificada como imagen Jpg."
type: docs
url: /es/go-cpp/convert/pagetojpg/
---

_Convertir y guardar la página especificada como imagen Jpg._

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
	// Open(filename string) abre un PDF-documento con el nombre de archivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// PageToJpg(num int32, resolution_dpi int32, filename string) guarda la página especificada como archivo de imagen Jpg
	err = pdf.PageToJpg(1, 100, "sample_page1.jpg")
	if err != nil {
		log.Fatal(err)
	}
}
```
