---
title: "RemoveAttachments"
second_title: "Aspose.PDF para Go vía C++"
description: "Eliminar adjuntos de PDF-document."
type: docs
url: /es/go-cpp/organize/removeattachments/
---

_Elimina los adjuntos del PDF-document._

```go
func (document *Document) RemoveAttachments() error
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
	// RemoveAttachments() elimina los adjuntos del PDF-document
	err = pdf.RemoveAttachments()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_RemoveAttachments.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
