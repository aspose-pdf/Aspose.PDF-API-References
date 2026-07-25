---
title: "PageRemoveImages"
second_title: "Aspose.PDF pour Go via C++"
description: "Supprimer les images de la page."
type: docs
url: /fr/go-cpp/organize/pageremoveimages/
---

_Supprimer les images de la page._

```go
func (document *Document) PageRemoveImages(num int32) error
```

**Parameters**: 
  * **num** - page number of the PDF-document

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
	// PageRemoveImages(num int32) supprime les images de la page
	err = pdf.PageRemoveImages(1)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) enregistre le PDF-document précédemment ouvert avec un nouveau nom de fichier
	err = pdf.SaveAs("sample_page1_RemoveImages.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
