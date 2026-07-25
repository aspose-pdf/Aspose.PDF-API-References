---
title: "Новый"
second_title: "Aspose.PDF для Go через C++"
description: "Создать новый PDF-document."
type: docs
url: /ru/go-cpp/core/new/
---

_Создать новый PDF-документ._

```go
func New() (*Document, error)
```

**Parameters**: 

**Return**:
  * **\*Document** - pointer to document
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// New создает новый PDF-документ
	pdf, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() освобождает выделенные ресурсы для PDF-документа
	defer pdf.Close()
	// SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
	err = pdf.SaveAs("sample_New_SaveAs.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
