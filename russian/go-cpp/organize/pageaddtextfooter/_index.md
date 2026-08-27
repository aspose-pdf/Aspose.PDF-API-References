---
title: "PageAddTextFooter"
second_title: "Aspose.PDF для Go через C++"
description: "Добавить текст в нижний колонтитул страницы."
type: docs
url: /ru/go-cpp/organize/pageaddtextfooter/
---

_Добавить текст в нижний колонтитул страницы._

```go
func (document *Document) PageAddTextFooter(num int32, footer string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **footer** - pages footer

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
	// PageAddTextFooter(num int32, footer string) добавляет текст в нижний колонтитул страницы
	err = pdf.PageAddTextFooter(1, "Footer")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
	err = pdf.SaveAs("sample_PageAddTextFooter.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
