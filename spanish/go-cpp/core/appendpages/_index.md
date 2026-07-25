---
title: "AppendPages"
second_title: "Aspose.PDF para Go vía C++"
description: "Agregar páginas seleccionadas de otro documento PDF."
type: docs
url: /es/go-cpp/core/appendpages/
---

_Añade páginas seleccionadas de otro documento PDF._

```go
func (document *Document) AppendPages(anotherdocument *Document, pagerange string) error
```

**Parameters**: 
  * **anotherdocument** - reference to PDF-document instance
  * **pagerange** - string that specifies which pages to append. Supports individual pages, ranges, and open-ended intervals. For example: "1,3,5", "2-4", "-3", "4-", or "-" for all pages

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) abre un PDF-documento con el nombre de archivo
	pdf, err := asposepdf.Open("sample1page.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf.Close()
	// Open(filename string) abre otro PDF-documento con el nombre de archivo
	anotherpdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer anotherpdf.Close()
	// AppendPages(anotherdocument *Document, pagerange string) añade páginas específicas de otro documento PDF.
	err = pdf.AppendPages(anotherpdf, "1,3")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf.SaveAs("sample_AppendPages.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
