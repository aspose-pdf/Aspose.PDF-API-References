---
title: "IsLinearized"
second_title: "Aspose.PDF pour Go via C++"
description: "Obtenir une valeur indiquant si le document est linéarisé."
type: docs
url: /fr/go-cpp/core/islinearized/
---

_Obtenir une valeur indiquant si le document est linéarisé._

```go
func (document *Document) IsLinearized() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is linearized
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
	// IsLinearized() obtient une valeur indiquant si le document est linéarisé
	isLinearized, _ := pdf.IsLinearized()
	if isLinearized {
		fmt.Println("IsLinearized() is true")
	} else {
		fmt.Println("IsLinearized() is false")
	}
}
```
