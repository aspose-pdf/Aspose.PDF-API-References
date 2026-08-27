---
title: "SaveAs"
second_title: "Aspose.PDF для Go через C++"
description: "Сохранить ранее открытый PDF-document с новым именем файла."
type: docs
url: /ru/go-cpp/core/saveas/
---

_Сохранить ранее открытый PDF-документ с новым именем файла._

```go
func (document *Document) SaveAs(filename string) error
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
