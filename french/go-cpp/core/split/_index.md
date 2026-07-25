---
title: "Split"
second_title: "Aspose.PDF pour Go via C++"
description: "Créer plusieurs nouveaux documents PDF en extrayant des pages du document PDF actuel."
type: docs
url: /fr/go-cpp/core/split/
---

_Créer plusieurs nouveaux PDF-documents en extrayant des pages du PDF-document actuel._

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
	// Open(filename string) ouvre un PDF-document avec filename
	pdf_split, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libère les ressources allouées pour le PDF-document
	defer pdf_split.Close()

	// Split(pagerange string) crée plusieurs nouveaux PDF-documents en extrayant des pages du PDF-document actuel
	pdfs, err := pdf_split.Split("1-2;3;4-")
	if err != nil {
		log.Fatal(err)
	}

	// Enregistrer chaque PDF-document découpé comme un fichier séparé
	for i, pdf := range pdfs {
		defer pdf.Close()
		filename := fmt.Sprintf("sample_Split_part%d.pdf", i+1)
		// SaveAs(filename string) enregistre le PDF-document précédemment ouvert avec un nouveau nom de fichier
		err := pdf.SaveAs(filename)
		if err != nil {
			log.Fatal(err)
		}
	}
}
```
