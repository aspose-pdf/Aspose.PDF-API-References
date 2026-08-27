---
title: "AddPageNum"
second_title: "Aspose.PDF для Go через C++"
description: "Добавить номер страницы в PDF-документ."
type: docs
url: /ru/go-cpp/organize/addpagenum/
---

_Добавить номер страницы в PDF-документ._

```go
func (document *Document) AddPageNum() error
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
	// AddPageNum() добавляет номер страницы в PDF-документ
	err = pdf.AddPageNum()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
	err = pdf.SaveAs("sample_AddPageNum.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
