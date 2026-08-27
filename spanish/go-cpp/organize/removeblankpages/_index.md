---
title: "RemoveBlankPages"
second_title: "Aspose.PDF para Go vía C++"
description: "Eliminar páginas en blanco de PDF-document."
type: docs
url: /es/go-cpp/organize/removeblankpages/
---

_Eliminar páginas en blanco de PDF-document._

```go
func (document *Document) RemoveBlankPages() error
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
	// RemoveBlankPages() elimina páginas en blanco de PDF-document
	err = pdf.RemoveBlankPages()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_RemoveBlankPages.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
