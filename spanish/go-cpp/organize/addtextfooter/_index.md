---
title: "AddTextFooter"
second_title: "Aspose.PDF para Go vía C++"
description: "Agregar texto en el pie de página de un PDF-document."
type: docs
url: /es/go-cpp/organize/addtextfooter/
---

_Agregar texto en el pie de página de PDF-document._

```go
func (document *Document) AddTextFooter(footer string) error
```

**Parameters**: 
  * **footer** - pages footer

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
	// AddTextFooter(footer string) agrega texto en el pie de página de PDF-document
	err = pdf.AddTextFooter("Footer")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_AddTextFooter.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
