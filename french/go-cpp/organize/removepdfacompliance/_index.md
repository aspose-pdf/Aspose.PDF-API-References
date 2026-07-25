---
title: "RemovePdfaCompliance"
second_title: "Aspose.PDF pour Go via C++"
description: "Supprimer la conformité PDF/A d'un document PDF."
type: docs
url: /fr/go-cpp/organize/removepdfacompliance/
---

_Supprimer la conformité PDF/A d'un PDF-document._

```go
func (document *Document) RemovePdfaCompliance() error
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
	// RemovePdfaCompliance() supprime la conformité PDF/A du PDF-document
	err = pdf.RemovePdfaCompliance()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) enregistre le PDF-document précédemment ouvert avec un nouveau nom de fichier
	err = pdf.SaveAs("sample_RemovePdfaCompliance.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
