---
title: "PageToSvg"
second_title: "Aspose.PDF para Go vía C++"
description: "Convertir y guardar la página especificada como Svg-image."
type: docs
url: /es/go-cpp/convert/pagetosvg/
---

_Convertir y guardar la página especificada como imagen Svg._

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
	// Open(filename string) abre un PDF-documento con el nombre de archivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// PageToSvg(num int32, filename string) guarda la página especificada como archivo de imagen Svg
	err = pdf.PageToSvg(1, "sample_page1.svg")
	if err != nil {
		log.Fatal(err)
	}
}
```
