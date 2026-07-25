---
title: "SplitAtPage"
second_title: "Aspose.PDF para Go vía C++"
description: "Dividir el documento PDF en dos documentos PDF nuevos."
type: docs
url: /es/go-cpp/core/splitatpage/
---

_Divide el documento PDF en dos nuevos documentos PDF._

```go
func SplitAtPage(document *Document, page int) (*Document, *Document, error)
```

**Parameters**: 
  * **document** - pointer to document
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

	// SplitAtPage(document *Document, page int) crea dos nuevos documentos PDF
	left, right, err := asposepdf.SplitAtPage(pdf_split, 2)
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para los documentos PDF resultantes
	defer left.Close()
	defer right.Close()

	// Guarda cada parte como un archivo separado
	err = left.SaveAs("sample_SplitAtPage_left.pdf")
	if err != nil {
		log.Fatal(err)
	}
	err = right.SaveAs("sample_SplitAtPage_right.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
