---
title: "SaveTeX"
second_title: "Aspose.PDF для Go через C++"
description: "Преобразовать и сохранить ранее открытый PDF-документ как TeX-документ."
type: docs
url: /ru/go-cpp/convert/savetex/
---

_Конвертировать и сохранить ранее открытый PDF-document как TeX-document._

```go
func (document *Document) SaveTeX(filename string) error
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
	// SaveTeX(filename string) сохраняет ранее открытый PDF-document как TeX-document с именем файла
	err = pdf.SaveTeX("sample.tex")
	if err != nil {
		log.Fatal(err)
	}
}
```
