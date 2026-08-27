---
title: "AddTextHeader"
second_title: "Aspose.PDF para Go vía C++"
description: "Agregar texto en el encabezado de un PDF-document."
type: docs
url: /es/go-cpp/organize/addtextheader/
---

_Agregar texto en el encabezado de un documento PDF._

```go
func (document *Document) AddTextHeader(header string) error
```

**Parameters**: 
  * **header** - pages header

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
	// AddTextHeader(header string) agrega texto en el encabezado de un documento PDF
	err = pdf.AddTextHeader("Header")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_AddTextHeader.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
