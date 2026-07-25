---
title: "Save"
second_title: "Aspose.PDF pour Go via C++"
description: "Enregistrer le document PDF précédemment ouvert."
type: docs
url: /fr/go-cpp/core/save/
---

_Enregistrer le PDF-document précédemment ouvert._

```go
func (document *Document) Save() error
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
	// Save() enregistre le PDF-document précédemment ouvert
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
