---
title: "PageAdd"
second_title: "Aspose.PDF для Go через C++"
description: "Добавить новую страницу в PDF-документ."
type: docs
url: /ru/go-cpp/core/pageadd/
---

_Добавить новую страницу в PDF-документ._

```go
func (document *Document) PageAdd() error
```

**Parameters**: 

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
	// PageAdd() добавляет новую страницу в PDF-документ
	err = pdf.PageAdd()
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
