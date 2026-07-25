---
title: "SaveEpub"
second_title: "Aspose.PDF для Go через C++"
description: "Преобразовать и сохранить ранее открытый PDF-документ как Epub-документ."
type: docs
url: /ru/go-cpp/convert/saveepub/
---

_Преобразовать и сохранить ранее открытый PDF-документ как Epub-документ._

```go
func (document *Document) SaveEpub(filename string) error
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
	// SaveEpub(filename string) сохраняет ранее открытый PDF-документ как Epub-документ с именем файла
	err = pdf.SaveEpub("sample.epub")
	if err != nil {
		log.Fatal(err)
	}
}
```
