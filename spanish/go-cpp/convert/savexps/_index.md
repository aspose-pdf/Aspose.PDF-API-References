---
title: "SaveXps"
second_title: "Aspose.PDF para Go vía C++"
description: "Convertir y guardar el PDF-documento previamente abierto como documento Xps."
type: docs
url: /es/go-cpp/convert/savexps/
---

_Convertir y guardar el PDF-documento previamente abierto como documento Xps._

```go
func (document *Document) SaveXps(filename string) error
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
	// SaveXps(filename string) guarda el PDF-documento previamente abierto como documento Xps con el nombre de archivo
	err = pdf.SaveXps("sample.xps")
	if err != nil {
		log.Fatal(err)
	}
}
```
