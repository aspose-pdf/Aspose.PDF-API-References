---
title: "SaveDoc"
second_title: "Aspose.PDF pour Go via C++"
description: "Convertir et enregistrer le PDF-document précédemment ouvert au format Doc-document."
type: docs
url: /fr/go-cpp/convert/savedoc/
---

_Convertir et enregistrer le PDF-document précédemment ouvert en document Doc._

```go
func (document *Document) SaveDoc(filename string) error
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
	// Open(filename string) ouvre un PDF-document avec filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libère les ressources allouées pour le PDF-document
	defer pdf.Close()
	// SaveDoc(filename string) enregistre le PDF-document précédemment ouvert en document Doc avec le nom de fichier
	err = pdf.SaveDoc("sample.doc")
	if err != nil {
		log.Fatal(err)
	}
}
```
