---
title: "PageLayers"
second_title: "Aspose.PDF for Go via C++"
description: "Sayfadaki katman adlarını al."
type: docs
url: /tr/go-cpp/organize/pagelayers/
---

_Sayfadaki katmanların adlarını al._

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
	// Open(filename string) dosya adıyla bir PDF-belgesi açar
	pdf, err := asposepdf.Open("sample_layers.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf.Close()

	// PageLayers(num int32) sayfadaki katmanların adlarını alır
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
