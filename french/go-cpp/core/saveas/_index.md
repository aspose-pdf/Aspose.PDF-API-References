---
title: "SaveAs"
second_title: "Aspose.PDF pour Go via C++"
description: "Enregistrer le document PDF précédemment ouvert avec un nouveau nom de fichier."
type: docs
url: /fr/go-cpp/core/saveas/
---

_Enregistrez le PDF-document précédemment ouvert avec un nouveau nom de fichier._

```go
func (document *Document) SaveAs(filename string) error
```

**Parameters**: 
  * **filename** - new filename

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// New crée un nouveau PDF-document
	pdf, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() libère les ressources allouées pour le PDF-document
	defer pdf.Close()
	// SaveAs(filename string) enregistre le PDF-document précédemment ouvert avec un nouveau nom de fichier
	err = pdf.SaveAs("sample_New_SaveAs.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
