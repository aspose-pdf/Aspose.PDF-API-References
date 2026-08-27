---
title: "ExportXfdf"
second_title: "Aspose.PDF для Go через C++"
description: "Экспортировать из ранее открытого PDF-документа с AcroForm в XFDF-документ."
type: docs
url: /ru/go-cpp/convert/exportxfdf/
---

_Экспортировать из ранее открытого PDF-документа с AcroForm в XFDF-документ._

```go
func (document *Document) ExportXfdf(filename string) error
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
	// ExportXfdf(filename string) экспортирует из ранее открытого PDF-документа с AcroForm в XFDF-документ с именем файла
	err = pdf.ExportXfdf("sample.xfdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
