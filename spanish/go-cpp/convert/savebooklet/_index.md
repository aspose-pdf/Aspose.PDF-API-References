---
title: "SaveBooklet"
second_title: "Aspose.PDF para Go vía C++"
description: "Convertir y guardar el PDF-documento previamente abierto como PDF-documento de folleto."
type: docs
url: /es/go-cpp/convert/savebooklet/
---

_Convertir y guardar el PDF-documento previamente abierto como PDF-documento de folleto._

```go
func (document *Document) SaveBooklet(filename string) error
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
	// SaveBooklet(filename string) guarda el PDF-documento previamente abierto como PDF-documento de folleto con el nombre de archivo
	err = pdf.SaveBooklet("sample_Booklet.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
