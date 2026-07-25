---
title: "SaveBooklet"
second_title: "Aspose.PDF для Go через C++"
description: "Преобразовать и сохранить ранее открытый PDF-документ как PDF-документ брошюры."
type: docs
url: /ru/go-cpp/convert/savebooklet/
---

_Преобразовать и сохранить ранее открытый PDF-документ как буклет PDF-документ._

```go
func (document *Document) SaveBooklet(filename string) error
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
	// SaveBooklet(filename string) сохраняет ранее открытый PDF-документ как буклет PDF-документ с именем файла
	err = pdf.SaveBooklet("sample_Booklet.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
