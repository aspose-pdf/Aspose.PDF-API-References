---
title: "IsPdfaCompliant"
second_title: "Aspose.PDF pour Go via C++"
description: "Déterminer si un document PDF est conforme PDF/A."
type: docs
url: /fr/go-cpp/organize/ispdfacompliant/
---

_Get est un PDF-document conforme PDF/A._

```go
func (document *Document) IsPdfaCompliant() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is PDF/A compliant
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) ouvre un PDF-document avec filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libère les ressources allouées pour le PDF-document
	defer pdf.Close()
	// IsPdfaCompliant() obtient le statut de conformité PDF/A du PDF-document
	isPdfa, _ := pdf.IsPdfaCompliant()
	if isPdfa {
		fmt.Println("IsPdfaCompliant() is true")
	} else {
		fmt.Println("IsPdfaCompliant() is false")
	}
}
```
