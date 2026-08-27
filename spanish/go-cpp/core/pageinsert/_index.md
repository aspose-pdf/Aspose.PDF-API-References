---
title: "PageInsert"
second_title: "Aspose.PDF para Go vía C++"
description: "Insertar una nueva página en la posición especificada del documento PDF."
type: docs
url: /es/go-cpp/core/pageinsert/
---

_Inserta una nueva página en la posición especificada del documento PDF._

```go
func (document *Document) PageInsert(num int32) error
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
	// PageInsert(num int32) inserta una nueva página en la posición especificada del documento PDF
	err = pdf.PageInsert(1)
	if err != nil {
		log.Fatal(err)
	}
	// Save() guarda el PDF-documento previamente abierto
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
