---
title: "SaveAs"
second_title: "Aspose.PDF para Go vía C++"
description: "Guardar el documento PDF abierto previamente con un nuevo nombre de archivo."
type: docs
url: /es/go-cpp/core/saveas/
---

_Guarde el PDF-documento previamente abierto con un nuevo nombre de archivo._

```go
func (document *Document) SaveAs(filename string) error
```

**Parameters**: 
  * **filename** - new filename

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// New crea un nuevo PDF-documento
	pdf, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_New_SaveAs.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
