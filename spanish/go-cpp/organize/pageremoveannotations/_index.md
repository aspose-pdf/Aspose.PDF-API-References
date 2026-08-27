---
title: "PageRemoveAnnotations"
second_title: "Aspose.PDF para Go vía C++"
description: "Eliminar anotaciones en la página."
type: docs
url: /es/go-cpp/organize/pageremoveannotations/
---

_Eliminar anotaciones en la página._

```go
func (document *Document) PageRemoveAnnotations(num int32) error
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
	// PageRemoveAnnotations(num int32) elimina anotaciones en la página
	err = pdf.PageRemoveAnnotations(1)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_page1_RemoveAnnotations.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
