---
title: "PageReplaceText"
second_title: "Aspose.PDF для Go через C++"
description: "Заменить текст на странице."
type: docs
url: /ru/go-cpp/organize/pagereplacetext/
---

_Заменить текст на странице._

```go
func (document *Document) PageReplaceText(num int32, findText, replaceText string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **findText** - text fragment to search
  * **replaceText** - text fragment to replace

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
	// PageReplaceText(num int32, findText, replaceText string) заменяет текст на странице
	err = pdf.PageReplaceText(1, "PDF", "TXT")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
	err = pdf.SaveAs("sample_page1_ReplaceText.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
