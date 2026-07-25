---
title: "Split"
second_title: "Aspose.PDF para Go vía C++"
description: "Crear varios documentos PDF nuevos extrayendo páginas del documento PDF actual."
type: docs
url: /es/go-cpp/core/split/
---

_Crea varios documentos PDF nuevos extrayendo páginas del documento PDF actual._

```go
func (document *Document) Split(pagerange string) ([]*Document, error)
```

**Parameters**: 
  * **pagerange** - string that defines how to split the PDF-document. Each segment, separated by `;`, specifies the page range for a separate output PDF document. The page range syntax supports individual pages, ranges, and open-ended intervals. For example: "1,3,5;7-10", "-3;4-", or "1;2-3;5-"

**Return**: 
  * **[]\*Document** - slice of new PDF-documents, each containing the pages defined by a corresponding segment of the specified page range
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
	"fmt"
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

	// Split(pagerange string) crea varios documentos PDF nuevos extrayendo páginas del documento PDF actual
	pdfs, err := pdf_split.Split("1-2;3;4-")
	if err != nil {
		log.Fatal(err)
	}

	// Guarda cada documento PDF dividido como un archivo separado
	for i, pdf := range pdfs {
		defer pdf.Close()
		filename := fmt.Sprintf("sample_Split_part%d.pdf", i+1)
		// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
		err := pdf.SaveAs(filename)
		if err != nil {
			log.Fatal(err)
		}
	}
}
```
