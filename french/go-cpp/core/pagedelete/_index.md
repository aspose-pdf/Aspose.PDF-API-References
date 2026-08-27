---
title: "PageDelete"
second_title: "Aspose.PDF pour Go via C++"
description: "Supprimer la page spécifiée du PDF-document."
type: docs
url: /fr/go-cpp/core/pagedelete/
---

_Supprime la page spécifiée dans le PDF-document._

```go
func (document *Document) PageDelete(num int32) error
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
	// PageDelete(num int32) supprime la page spécifiée dans le PDF-document
	err = pdf.PageDelete(1)
	if err != nil {
		log.Fatal(err)
	}
	// Save() enregistre le PDF-document précédemment ouvert
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
