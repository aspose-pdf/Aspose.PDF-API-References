---
title: "Repair"
second_title: "Aspose.PDF para Go vía C++"
description: "Reparar PDF-document."
type: docs
url: /es/go-cpp/organize/repair/
---

_Reparar documento PDF._

```go
func (document *Document) Repair() error
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
	// Repair() repara el documento PDF
	err = pdf.Repair()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_Repair.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
