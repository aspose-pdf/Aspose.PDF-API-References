---
title: "PageAddTextFooter"
second_title: "Aspose.PDF para Go vía C++"
description: "Agregar texto en el pie de página."
type: docs
url: /es/go-cpp/organize/pageaddtextfooter/
---

_Añade texto en el pie de página._

```go
func (document *Document) PageAddTextFooter(num int32, footer string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
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
	// PageAddTextFooter(num int32, footer string) añade texto en el pie de página
	err = pdf.PageAddTextFooter(1, "Footer")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_PageAddTextFooter.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
