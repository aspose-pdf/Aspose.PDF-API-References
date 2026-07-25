---
title: "SaveDoc"
second_title: "Aspose.PDF para Go vía C++"
description: "Convertir y guardar el PDF-documento previamente abierto como documento Doc."
type: docs
url: /es/go-cpp/convert/savedoc/
---

_Convertir y guardar el PDF abierto previamente como documento Doc._

```go
func (document *Document) SaveDoc(filename string) error
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
	// SaveDoc(filename string) guarda el PDF abierto previamente como documento Doc con el nombre de archivo
	err = pdf.SaveDoc("sample.doc")
	if err != nil {
		log.Fatal(err)
	}
}
```
