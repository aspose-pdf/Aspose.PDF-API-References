---
title: "SplitAt"
second_title: "Aspose.PDF para Go vía C++"
description: "Dividir el documento PDF actual en dos documentos PDF nuevos."
type: docs
url: /es/go-cpp/core/splitat/
---

_Divide el documento PDF actual en dos documentos PDF nuevos._

```go
func (document *Document) SplitAt(page int) (*Document, *Document, error)
```

**Parameters**: 
  * **page** - page number at which to split the PDF-document. Pages up to and including this page go into the first PDF-document

**Return**: 
  * **\*Document** - new PDF-document containing pages 1 to page (inclusive)
  * **\*Document** - new PDF-document containing pages from page + 1 to the end
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
	"github.com/aspose-pdf/aspose-pdf-go-cpp"
	"log"
)

func main() {
	// Open(filename string) abre un PDF-documento con el nombre de archivo
	pdf_split, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf_split.Close()

	// SplitAt(page int) divide el documento PDF actual en dos documentos PDF nuevos.
	left, right, err := pdf_split.SplitAt(2)
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para los documentos PDF resultantes
	defer left.Close()
	defer right.Close()

	// Guarda cada parte como un archivo separado
	err = left.SaveAs("sample_SplitAt_left.pdf")
	if err != nil {
		log.Fatal(err)
	}
	err = right.SaveAs("sample_SplitAt_right.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
