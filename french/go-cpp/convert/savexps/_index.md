---
title: "SaveXps"
second_title: "Aspose.PDF pour Go via C++"
description: "Convertir et enregistrer le PDF-document précédemment ouvert au format Xps-document."
type: docs
url: /fr/go-cpp/convert/savexps/
---

_Convertir et enregistrer le PDF-document précédemment ouvert en document Xps._

```go
func (document *Document) SaveXps(filename string) error
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
	// SaveXps(filename string) enregistre le PDF-document précédemment ouvert en document Xps avec filename
	err = pdf.SaveXps("sample.xps")
	if err != nil {
		log.Fatal(err)
	}
}
```
