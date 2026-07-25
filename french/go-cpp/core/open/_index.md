---
title: "Open"
second_title: "Aspose.PDF pour Go via C++"
description: "Ouvrir un document PDF avec le nom de fichier."
type: docs
url: /fr/go-cpp/core/open/
---

_Ouvre un PDF-document avec le nom de fichier._

```go
func Open(filename string) (*Document, error)
```

**Parameters**: 
  * **\*Document** - pointer to document
  * **filename** - full file name of the PDF-document

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
	// Save() enregistre le PDF-document précédemment ouvert
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
