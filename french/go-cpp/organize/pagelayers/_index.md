---
title: "PageLayers"
second_title: "Aspose.PDF pour Go via C++"
description: "Obtient les noms des couches sur la page."
type: docs
url: /fr/go-cpp/organize/pagelayers/
---

_Obtient les noms des calques sur la page._

```go
func (document *Document) PageLayers(num int32) ([]string, error)
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **[]string** - contains an array layers' names
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
	"fmt"
	"github.com/aspose-pdf/aspose-pdf-go-cpp"
	"log"
)

func main() {
	// Open(filename string) ouvre un PDF-document avec filename
	pdf, err := asposepdf.Open("sample_layers.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libère les ressources allouées pour le PDF-document
	defer pdf.Close()

	// PageLayers(num int32) obtient les noms des calques sur la page
	layers, err := pdf.PageLayers(1)
	if err != nil {
		log.Fatal(err)
	}

	fmt.Println("Layers on page 1:")
	for i, layer := range layers {
		fmt.Printf("  [%d] %s\n", i, layer)
	}
}
```
