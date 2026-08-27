---
title: "RemoveSigns"
second_title: "Aspose.PDF para Go vía C++"
description: "Eliminar firmas del documento PDF."
type: docs
url: /es/go-cpp/security/removesigns/
---

_Eliminar firmas de PDF-document._

```go
func (document *Document) RemoveSigns(filename string) error
```

**Parameters**: 
  * **filename** - new filename, without signs

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) abre un PDF-documento con el nombre de archivo
	pdf, err := asposepdf.Open("sample_with_sign.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// RemoveSigns(filename string) elimina firmas de PDF-document
	err = pdf.RemoveSigns("sample_RemoveSigns.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
