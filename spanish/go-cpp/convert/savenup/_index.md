---
title: "SaveNUp"
second_title: "Aspose.PDF para Go vía C++"
description: "Convertir y guardar el PDF-documento previamente abierto como PDF-documento N-Up."
type: docs
url: /es/go-cpp/convert/savenup/
---

_Convierte y guarda el PDF-document previamente abierto como PDF-documento N-Up._

```go
func (document *Document) SaveNUp(filename string, columns int32, rows int32) error
```

**Parameters**: 
  * **filename** - new filename
  * **columns** - number of columns
  * **rows** - number of rows

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
	// SaveNUp(filename string, columns int32, rows int32) guarda el PDF-document previamente abierto como PDF-documento N-Up con filename
	err = pdf.SaveNUp("sample_NUp.pdf", 2, 2)
	if err != nil {
		log.Fatal(err)
	}
}
```
