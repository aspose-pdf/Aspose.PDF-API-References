---
title: "SaveXps"
second_title: "Aspose.PDF для Go через C++"
description: "Преобразовать и сохранить ранее открытый PDF-документ как Xps-документ."
type: docs
url: /ru/go-cpp/convert/savexps/
---

_Преобразовать и сохранить ранее открытый PDF-документ как Xps-документ._

```go
func (document *Document) SaveXps(filename string) error
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
	// SaveXps(filename string) сохраняет ранее открытый PDF-документ как Xps-документ с именем файла
	err = pdf.SaveXps("sample.xps")
	if err != nil {
		log.Fatal(err)
	}
}
```
