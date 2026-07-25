---
title: "MergeDocuments"
second_title: "Aspose.PDF para Go vía C++"
description: "Crear un nuevo documento PDF combinando los documentos PDF proporcionados."
type: docs
url: /es/go-cpp/core/mergedocuments/
---

_Crea un nuevo documento PDF combinando los documentos PDF proporcionados._

```go
func MergeDocuments(documents []*Document) (*Document, error)
```

**Parameters**: 
  * **documents** - slice of PDF-documents to be merged

**Return**: 
  * **\*Document** - new PDF-document containing all pages from the provided PDF-documents
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// New crea un nuevo PDF-documento
	pdf1, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf1.Close()
	err = pdf1.PageAdd()
	if err != nil {
		log.Fatal(err)
	}
	// Open(filename string) abre un PDF-documento con el nombre de archivo
	pdf2, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf2.Close()
	// MergeDocuments(documents []*Document) crea un nuevo documento PDF al combinar los documentos proporcionados.
	pdf_merged, err := asposepdf.MergeDocuments([]*asposepdf.Document{pdf1, pdf2})
	if err != nil {
		log.Fatal(err)
	}
	// Close() libera los recursos asignados para el PDF-documento
	defer pdf_merged.Close()
	// SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
	err = pdf_merged.SaveAs("sample_MergeDocuments.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
