---
title: "Open"
second_title: "Aspose.PDF para Go vía C++"
description: "Abrir un documento PDF con nombre de archivo."
type: docs
url: /es/go-cpp/core/open/
---

_Abre un PDF-documento con el nombre de archivo._

```go
func Open(filename string) (*Document, error)
```

**Parameters**: 
  * **\*Document** - pointer to document
  * **filename** - full file name of the PDF-document

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
	// Save() guarda el PDF-documento previamente abierto
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
