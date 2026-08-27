---
title: "ExportXml"
second_title: "Aspose.PDF для Go через C++"
description: "Экспортировать из ранее открытого PDF-документа с AcroForm в XML-документ."
type: docs
url: /ru/go-cpp/convert/exportxml/
---

_Экспортировать из ранее открытого PDF-документа с AcroForm в XML-документ._

```go
func (document *Document) ExportXml(filename string) error
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
	// ExportXml(filename string) экспортирует из ранее открытого PDF-документа с AcroForm в XML-документ с именем файла
	err = pdf.ExportXml("sample.xml")
	if err != nil {
		log.Fatal(err)
	}
}
```
