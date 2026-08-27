---
title: "AddTextHeader"
second_title: "Aspose.PDF для Go через C++"
description: "Добавить текст в заголовок PDF-документа."
type: docs
url: /ru/go-cpp/organize/addtextheader/
---

_Добавить текст в заголовок PDF-документа._

```go
func (document *Document) AddTextHeader(header string) error
```

**Parameters**: 
  * **header** - pages header

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
	// AddTextHeader(header string) добавляет текст в заголовок PDF-документа
	err = pdf.AddTextHeader("Header")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
	err = pdf.SaveAs("sample_AddTextHeader.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
