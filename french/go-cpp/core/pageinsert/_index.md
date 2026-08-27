---
title: "PageInsert"
second_title: "Aspose.PDF pour Go via C++"
description: "Insérer une nouvelle page à la position spécifiée dans le PDF-document."
type: docs
url: /fr/go-cpp/core/pageinsert/
---

_Insérer une nouvelle page à la position spécifiée dans le PDF-document._

```go
func (document *Document) PageInsert(num int32) error
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
	// PageInsert(num int32) insère une nouvelle page à la position spécifiée dans le PDF-document
	err = pdf.PageInsert(1)
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
