---
title: "PageLayers"
second_title: "Aspose.PDF für Go über C++"
description: "Ermittelt die Namen der Ebenen auf der Seite."
type: docs
url: /de/go-cpp/organize/pagelayers/
---

_Ermittelt die Namen der Ebenen auf der Seite._

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
	// Open(filename string) öffnet ein PDF-document mit Dateiname
	pdf, err := asposepdf.Open("sample_layers.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() gibt zugewiesene Ressourcen für PDF-document frei
	defer pdf.Close()

	// PageLayers(num int32) ermittelt die Namen der Ebenen auf der Seite
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
