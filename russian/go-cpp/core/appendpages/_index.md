---
title: "AppendPages"
second_title: "Aspose.PDF для Go через C++"
description: "Добавить выбранные страницы из другого PDF-document."
type: docs
url: /ru/go-cpp/core/appendpages/
---

_Добавить выбранные страницы из другого PDF-документа._

```go
func (document *Document) AppendPages(anotherdocument *Document, pagerange string) error
```

**Parameters**: 
  * **anotherdocument** - reference to PDF-document instance
  * **pagerange** - string that specifies which pages to append. Supports individual pages, ranges, and open-ended intervals. For example: "1,3,5", "2-4", "-3", "4-", or "-" for all pages

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) открывает PDF-документ с именем файла
	pdf, err := asposepdf.Open("sample1page.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() освобождает выделенные ресурсы для PDF-документа
	defer pdf.Close()
	// Open(filename string) открывает другой PDF-документ с именем файла
	anotherpdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() освобождает выделенные ресурсы для PDF-документа
	defer anotherpdf.Close()
	// AppendPages(anotherdocument *Document, pagerange string) добавляет определённые страницы из другого PDF-документа.
	err = pdf.AppendPages(anotherpdf, "1,3")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
	err = pdf.SaveAs("sample_AppendPages.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
