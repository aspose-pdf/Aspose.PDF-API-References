---
title: "PageLayers"
second_title: "Aspose.PDF для Go через C++"
description: "Получает имена слоёв на странице."
type: docs
url: /ru/go-cpp/organize/pagelayers/
---

_Получает имена слоёв на странице._

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
	// Open(filename string) открывает PDF-документ с именем файла
	pdf, err := asposepdf.Open("sample_layers.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() освобождает выделенные ресурсы для PDF-документа
	defer pdf.Close()

	// PageLayers(num int32) получает имена слоёв на странице
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
