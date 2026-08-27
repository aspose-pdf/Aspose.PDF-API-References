---
title: "PageLayers"
second_title: "C++를 통한 Go용 Aspose.PDF"
description: "페이지의 레이어 이름을 가져옵니다."
type: docs
url: /ko/go-cpp/organize/pagelayers/
---

_페이지의 레이어 이름을 가져옵니다._

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
	// Open(filename string) filename을 사용하여 PDF-document을 엽니다
	pdf, err := asposepdf.Open("sample_layers.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-document에 할당된 리소스를 해제합니다
	defer pdf.Close()

	// PageLayers(num int32) 은 페이지의 레이어 이름을 가져옵니다
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
