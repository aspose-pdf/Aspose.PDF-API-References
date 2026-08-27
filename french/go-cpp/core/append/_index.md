---
title: "Append"
second_title: "Aspose.PDF pour Go via C++"
description: "Ajouter des pages d'un autre document PDF."
type: docs
url: /fr/go-cpp/core/append/
---

_Ajoute des pages d'un autre PDF-document._

```go
func (document *Document) Append(anotherdocument *Document) error
```

**Parameters**: 
  * **anotherdocument** - reference to PDF-document instance

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

	// Open(filename string) ouvre un autre PDF-document avec le nom de fichier
	anotherpdf, err := asposepdf.Open("sample1page.pdf")
	if err != nil {
		log.Fatal(err)
	}

	// Close() libère les ressources allouées pour le PDF-document
	defer anotherpdf.Close()

	// Append(anotherdocument *Document) ajoute des pages d'un autre PDF-document.
	err = pdf.Append(anotherpdf)
	if err != nil {
		log.Fatal(err)
	}

	// SaveAs(filename string) enregistre le PDF-document précédemment ouvert avec un nouveau nom de fichier
	err = pdf.SaveAs("sample_Append.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
