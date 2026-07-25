---
title: "PageAdd"
second_title: "Aspose.PDF pour Go via C++"
description: "Ajouter une nouvelle page dans le PDF-document."
type: docs
url: /fr/go-cpp/core/pageadd/
---

_Ajouter une nouvelle page dans le PDF-document._

```go
func (document *Document) PageAdd() error
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
	// PageAdd() ajoute une nouvelle page dans le PDF-document
	err = pdf.PageAdd()
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
