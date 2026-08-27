---
title: "PageAddText"
second_title: "Aspose.PDF для Go через C++"
description: "Добавить текст на страницу."
type: docs
url: /ru/go-cpp/organize/pageaddtext/
---

_Добавить текст на страницу._

```go
func (document *Document) PageAddText(num int32, addText string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **addText** - added text

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
	// PageAddText(num int32, addText string) добавляет текст на страницу
	err = pdf.PageAddText(1, "added text")
	if err != nil {
		log.Fatal(err)
	}
	// Save() сохраняет ранее открытый PDF-документ
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
