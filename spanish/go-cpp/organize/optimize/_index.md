---
title: "Optimize"
second_title: "Aspose.PDF para Go vía C++"
description: "Optimizar el contenido del PDF-document."
type: docs
url: /es/go-cpp/organize/optimize/
---

_Optimizar el contenido del documento PDF._

```go
func (document *Document) Optimize() error
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
	// Optimize() optimiza el contenido del documento PDF
	err = pdf.Optimize()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_Optimize.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
