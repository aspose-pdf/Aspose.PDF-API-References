---
title: "SaveEpub"
second_title: "Aspose.PDF para Go vía C++"
description: "Convertir y guardar el PDF-documento previamente abierto como documento Epub."
type: docs
url: /es/go-cpp/convert/saveepub/
---

_Convierte y guarda el PDF-document previamente abierto como documento Epub._

```go
func (document *Document) SaveEpub(filename string) error
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
	// SaveEpub(filename string) guarda el PDF-document previamente abierto como documento Epub con filename
	err = pdf.SaveEpub("sample.epub")
	if err != nil {
		log.Fatal(err)
	}
}
```
