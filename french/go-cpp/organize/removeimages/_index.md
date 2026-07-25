---
title: "RemoveImages"
second_title: "Aspose.PDF pour Go via C++"
description: "Supprimer les images du PDF-document."
type: docs
url: /fr/go-cpp/organize/removeimages/
---

_Supprimer les images du document PDF._

```go
func (document *Document) RemoveImages() error
```

**Parameters**: 

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
	// RemoveImages() supprime les images du document PDF
	err = pdf.RemoveImages()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) enregistre le PDF-document précédemment ouvert avec un nouveau nom de fichier
	err = pdf.SaveAs("sample_RemoveImages.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
