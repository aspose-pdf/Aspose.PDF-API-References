---
title: "RemoveTables"
second_title: "Aspose.PDF для Go через C++"
description: "Удалить таблицы из PDF-документа."
type: docs
url: /ru/go-cpp/organize/removetables/
---

_Удалить таблицы из PDF-документа._

```go
func (document *Document) RemoveTables() error
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
	// RemoveTables() удаляет таблицы из PDF-документа
	err = pdf.RemoveTables()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
	err = pdf.SaveAs("sample_RemoveTables.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
