---
title: "SavePptX"
second_title: "Aspose.PDF para Go vía C++"
description: "Convertir y guardar el PDF-documento previamente abierto como documento PptX."
type: docs
url: /es/go-cpp/convert/savepptx/
---

_Convierte y guarda el PDF-document previamente abierto como documento PptX._

```go
func (document *Document) SavePptX(filename string) error
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
	// Open(filename string) abre un PDF-documento con el nombre de archivo
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// SavePptX(filename string) guarda el PDF-document previamente abierto como documento PptX con filename
	err = pdf.SavePptX("sample.pptx")
	if err != nil {
		log.Fatal(err)
	}
}
```
