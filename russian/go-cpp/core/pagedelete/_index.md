---
title: "PageDelete"
second_title: "Aspose.PDF для Go через C++"
description: "Удалить указанную страницу из PDF-документа."
type: docs
url: /ru/go-cpp/core/pagedelete/
---

_Удалить указанную страницу в PDF-документе._

```go
func (document *Document) PageDelete(num int32) error
```

**Parameters**: 
  * **num** - page number of the PDF-document

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
	// PageDelete(num int32) удаляет указанную страницу в PDF-документе
	err = pdf.PageDelete(1)
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
