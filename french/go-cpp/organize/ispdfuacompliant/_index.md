---
title: "IsPdfUaCompliant"
second_title: "Aspose.PDF pour Go via C++"
description: "Déterminer si un document PDF est conforme PDF/UA."
type: docs
url: /fr/go-cpp/organize/ispdfuacompliant/
---

_Obtenir si un document PDF est conforme PDF/UA._

```go
func (document *Document) IsPdfUaCompliant() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is PDF/UA compliant
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
	// IsPdfUaCompliant() obtient le statut de conformité PDF/UA du document PDF
	isPdfua, _ := pdf.IsPdfUaCompliant()
	if isPdfua {
		fmt.Println("IsPdfUaCompliant() is true")
	} else {
		fmt.Println("IsPdfUaCompliant() is false")
	}
}
```
