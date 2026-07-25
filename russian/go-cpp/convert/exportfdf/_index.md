---
title: "ExportFdf"
second_title: "Aspose.PDF для Go через C++"
description: "Экспортировать из ранее открытого PDF-документа с AcroForm в FDF-документ."
type: docs
url: /ru/go-cpp/convert/exportfdf/
---

_Экспортировать из ранее открытого PDF-document с AcroForm в FDF-document._

```go
func (document *Document) ExportFdf(filename string) error
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
	// ExportFdf(filename string) экспортирует из ранее открытого PDF-document с AcroForm в FDF-document с именем файла
	err = pdf.ExportFdf("sample.fdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
