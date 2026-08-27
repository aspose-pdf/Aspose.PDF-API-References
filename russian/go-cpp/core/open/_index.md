---
title: "Open"
second_title: "Aspose.PDF для Go через C++"
description: "Открыть PDF-document с именем файла."
type: docs
url: /ru/go-cpp/core/open/
---

_Открыть PDF-документ с именем файла._

```go
func Open(filename string) (*Document, error)
```

**Parameters**: 
  * **\*Document** - pointer to document
  * **filename** - full file name of the PDF-document

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
	// Save() сохраняет ранее открытый PDF-документ
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
