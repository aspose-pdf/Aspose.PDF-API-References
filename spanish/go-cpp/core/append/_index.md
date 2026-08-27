---
title: "Append"
second_title: "Aspose.PDF para Go vía C++"
description: "Agregar páginas de otro documento PDF."
type: docs
url: /es/go-cpp/core/append/
---

_Añade páginas de otro PDF-documento._

```go
func (document *Document) Append(anotherdocument *Document) error
```

**Parameters**: 
  * **anotherdocument** - reference to PDF-document instance

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

	// Open(filename string) abre otro PDF-documento con el nombre de archivo
	anotherpdf, err := asposepdf.Open("sample1page.pdf")
	if err != nil {
		log.Fatal(err)
	}

	// Close() libera los recursos asignados para el PDF-documento
	defer anotherpdf.Close()

	// Append(anotherdocument *Document) añade páginas de otro PDF-documento.
	err = pdf.Append(anotherpdf)
	if err != nil {
		log.Fatal(err)
	}

	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_Append.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
