---
title: "PageAdd"
second_title: "Aspose.PDF para Go vía C++"
description: "Agregar una nueva página en el documento PDF."
type: docs
url: /es/go-cpp/core/pageadd/
---

_Añade una nueva página en el documento PDF._

```go
func (document *Document) PageAdd() error
```

**Parameters**: 

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
	// PageAdd() añade una nueva página en el documento PDF
	err = pdf.PageAdd()
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
