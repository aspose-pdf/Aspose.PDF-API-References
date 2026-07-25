---
title: "Repair"
second_title: "Aspose.PDF pour Go via C++"
description: "Réparer le PDF-document."
type: docs
url: /fr/go-cpp/organize/repair/
---

_Réparer le PDF-document._

```go
func (document *Document) Repair() error
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
	// Repair() répare le PDF-document
	err = pdf.Repair()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) enregistre le PDF-document précédemment ouvert avec un nouveau nom de fichier
	err = pdf.SaveAs("sample_Repair.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
