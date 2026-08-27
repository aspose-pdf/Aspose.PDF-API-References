---
title: "PageAddTextHeader"
second_title: "Aspose.PDF для Go через C++"
description: "Добавить текст в заголовок страницы."
type: docs
url: /ru/go-cpp/organize/pageaddtextheader/
---

_Добавить текст в заголовок страницы._

```go
func (document *Document) PageAddTextHeader(num int32, header string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
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
	// PageAddTextHeader(num int32, header string) добавляет текст в заголовок страницы
	err = pdf.PageAddTextHeader(1, "Header")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
	err = pdf.SaveAs("sample_PageAddTextHeader.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
