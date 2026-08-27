---
title: "RemoveHiddenText"
second_title: "Aspose.PDF para Go vía C++"
description: "Eliminar texto oculto de PDF-document."
type: docs
url: /es/go-cpp/organize/removehiddentext/
---

_Eliminar texto oculto del documento PDF._

```go
func (document *Document) RemoveHiddenText() error
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
	// RemoveHiddenText() elimina texto oculto del documento PDF
	err = pdf.RemoveHiddenText()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_RemoveHiddenText.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
