---
title: "EnregistrerTxt"
second_title: "Aspose.PDF pour Go via C++"
description: "Convertir et enregistrer le PDF-document précédemment ouvert au format Txt-document."
type: docs
url: /fr/go-cpp/convert/savetxt/
---

_Convertir et enregistrer le PDF-document précédemment ouvert en tant que document Txt._

```go
func (document *Document) SaveTxt(filename string) error
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
	// SaveTxt(filename string) enregistre le PDF-document précédemment ouvert en tant que document Txt avec le nom de fichier
	err = pdf.SaveTxt("sample.txt")
	if err != nil {
		log.Fatal(err)
	}
}
```
