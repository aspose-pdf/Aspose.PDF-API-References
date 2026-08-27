---
title: "SplitDocument"
second_title: "Aspose.PDF para Go vía C++"
description: "Crear varios documentos PDF nuevos extrayendo páginas del documento PDF fuente."
type: docs
url: /es/go-cpp/core/splitdocument/
---

_Crea varios documentos PDF nuevos extrayendo páginas del documento PDF fuente._

```go
func SplitDocument(document *Document, pagerange string) ([]*Document, error)
```

**Parameters**: 
  * **document** - pointer to document
  * **pagerange** - string that defines how to split the PDF-document. Each segment, separated by `;`, specifies the page range for a separate output PDF document. The page range syntax supports individual pages, ranges, and open-ended intervals. For example: "1,3,5;7-10", "-3;4-", or "1;2-3;5-"

**Return**: 
  * **[]\*Document** - slice of new PDF-documents, each containing the pages defined by a corresponding segment of the specified page range
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
	"fmt"
	"log"
	"github.com/aspose-pdf/aspose-pdf-go-cpp"
)

func main() {
	// Open(filename string) abre un PDF-documento con el nombre de archivo
	pdf_split, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf_split.Close()

	// SplitDocument(document *Document, pagerange string) crea varios documentos PDF nuevos
	pdfs, err := asposepdf.SplitDocument(pdf_split, "1-2;3;4-")
	if err != nil {
		log.Fatal(err)
	}

	// Guarda cada documento PDF dividido como un archivo separado
	for i, pdf := range pdfs {
		defer pdf.Close()
		filename := fmt.Sprintf("sample_SplitDocument_part%d.pdf", i+1)
		// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
		err := pdf.SaveAs(filename)
		if err != nil {
			log.Fatal(err)
		}
	}
}
```
