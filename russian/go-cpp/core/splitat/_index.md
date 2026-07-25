---
title: "SplitAt"
second_title: "Aspose.PDF для Go через C++"
description: "Разделить текущий PDF-document на два новых PDF-documents."
type: docs
url: /ru/go-cpp/core/splitat/
---

_Разделить текущий PDF-документ на два новых PDF-документа._

```go
func (document *Document) SplitAt(page int) (*Document, *Document, error)
```

**Parameters**: 
  * **page** - page number at which to split the PDF-document. Pages up to and including this page go into the first PDF-document

**Return**: 
  * **\*Document** - new PDF-document containing pages 1 to page (inclusive)
  * **\*Document** - new PDF-document containing pages from page + 1 to the end
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
	"github.com/aspose-pdf/aspose-pdf-go-cpp"
	"log"
)

func main() {
	// Open(filename string) открывает PDF-документ с именем файла
	pdf_split, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() освобождает выделенные ресурсы для PDF-документа
	defer pdf_split.Close()

	// SplitAt(page int) разделяет текущий PDF-документ на два новых PDF-документа.
	left, right, err := pdf_split.SplitAt(2)
	if err != nil {
		log.Fatal(err)
	}
	// Close() освобождает выделенные ресурсы для полученных PDF-документов
	defer left.Close()
	defer right.Close()

	// Сохранить каждую часть как отдельный файл
	err = left.SaveAs("sample_SplitAt_left.pdf")
	if err != nil {
		log.Fatal(err)
	}
	err = right.SaveAs("sample_SplitAt_right.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
