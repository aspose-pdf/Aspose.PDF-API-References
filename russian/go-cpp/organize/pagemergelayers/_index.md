---
title: "PageMergeLayers"
second_title: "Aspose.PDF для Go через C++"
description: "Объединить все слои на странице в один слой с указанным новым именем слоя."
type: docs
url: /ru/go-cpp/organize/pagemergelayers/
---

_Объединить все слои на странице в один слой с указанным новым именем слоя._

```go
func (document *Document) PageMergeLayers(num int32, newLayerName string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **newLayerName** - name of the new layer after merging

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
	// PageMergeLayers(num int32, newLayerName string) объединяет все слои на странице в один слой с указанным новым именем слоя
	err = pdf.PageMergeLayers(1, "newLayerName")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
	err = pdf.SaveAs("sample_PageMergeLayers.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
