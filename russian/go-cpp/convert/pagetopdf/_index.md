---
title: "PageToPdf"
second_title: "Aspose.PDF для Go через C++"
description: "Конвертировать и сохранить указанную страницу как Pdf."
type: docs
url: /ru/go-cpp/convert/pagetopdf/
---

_Конвертировать и сохранить указанную страницу как Pdf._

```go
func (document *Document) PageToPdf(num int32, filename string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
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
	// PageToPdf(num int32, filename string) сохраняет указанную страницу как Pdf-file
	err = pdf.PageToPdf(1, "sample_page1.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
