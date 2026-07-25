---
title: "SaveXlsX"
second_title: "Aspose.PDF pour Go via C++"
description: "Convertir et enregistrer le PDF-document précédemment ouvert au format XlsX-document."
type: docs
url: /fr/go-cpp/convert/savexlsx/
---

_Convertir et enregistrer le PDF-document précédemment ouvert en document XlsX._

```go
func (document *Document) SaveXlsX(filename string) error
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
	// SaveXlsX(filename string) enregistre le PDF-document précédemment ouvert en document XlsX avec filename
	err = pdf.SaveXlsX("sample.xlsx")
	if err != nil {
		log.Fatal(err)
	}
}
```
