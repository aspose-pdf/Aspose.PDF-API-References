---
title: "SplitAt"
second_title: "Aspose.PDF pour Go via C++"
description: "Diviser le document PDF actuel en deux nouveaux documents PDF."
type: docs
url: /fr/go-cpp/core/splitat/
---

_Diviser le document PDF actuel en deux nouveaux documents PDF._

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
	// Open(filename string) ouvre un PDF-document avec filename
	pdf_split, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libère les ressources allouées pour le PDF-document
	defer pdf_split.Close()

	// SplitAt(page int) divise le document PDF actuel en deux nouveaux documents PDF.
	left, right, err := pdf_split.SplitAt(2)
	if err != nil {
		log.Fatal(err)
	}
	// Close() libère les ressources allouées pour les documents PDF résultants
	defer left.Close()
	defer right.Close()

	// Enregistrer chaque partie comme un fichier séparé
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
