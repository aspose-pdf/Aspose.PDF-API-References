---
title: "PageAddTextHeader"
second_title: "Aspose.PDF pour Go via C++"
description: "Ajouter du texte dans l'en-tête de la page."
type: docs
url: /fr/go-cpp/organize/pageaddtextheader/
---

_Ajouter du texte dans l’en-tête de la page._

```go
func (document *Document) PageAddTextHeader(num int32, header string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **header** - pages header

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) ouvre un PDF-document avec filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libère les ressources allouées pour le PDF-document
	defer pdf.Close()
	// PageAddTextHeader(num int32, header string) ajoute du texte dans l’en-tête de la page
	err = pdf.PageAddTextHeader(1, "Header")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) enregistre le PDF-document précédemment ouvert avec un nouveau nom de fichier
	err = pdf.SaveAs("sample_PageAddTextHeader.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
