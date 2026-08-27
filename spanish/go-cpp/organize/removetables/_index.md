---
title: "RemoveTables"
second_title: "Aspose.PDF para Go vía C++"
description: "Eliminar tablas de PDF-document."
type: docs
url: /es/go-cpp/organize/removetables/
---

_Eliminar tablas de un documento PDF._

```go
func (document *Document) RemoveTables() error
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
	// RemoveTables() elimina tablas de un documento PDF
	err = pdf.RemoveTables()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_RemoveTables.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
