---
title: "PageAddText"
second_title: "Aspose.PDF pour Go via C++"
description: "Ajouter du texte sur la page."
type: docs
url: /fr/go-cpp/organize/pageaddtext/
---

_Ajouter du texte sur la page._

```go
func (document *Document) PageAddText(num int32, addText string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **addText** - added text

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
	// PageAddText(num int32, addText string) ajoute du texte sur la page
	err = pdf.PageAddText(1, "added text")
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
