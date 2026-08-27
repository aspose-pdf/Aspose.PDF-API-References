---
title: "SaveSvgZip"
second_title: "Aspose.PDF для Go через C++"
description: "Преобразовать и сохранить ранее открытый PDF-документ как SVG-архив."
type: docs
url: /ru/go-cpp/convert/savesvgzip/
---

_Преобразовать и сохранить ранее открытый PDF-документ как SVG-архив._

```go
func (document *Document) SaveSvgZip(filename string) error
```

**Parameters**: 
  * **filename** - new filename

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) открывает PDF-документ с именем файла
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() освобождает выделенные ресурсы для PDF-документа
	defer pdf.Close()
	// SaveSvgZip(filename string) сохраняет ранее открытый PDF-документ как SVG-архив с именем файла
	err = pdf.SaveSvgZip("sample_svg.zip")
	if err != nil {
		log.Fatal(err)
	}
}
```
