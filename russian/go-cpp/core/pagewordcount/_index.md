---
title: "PageWordCount"
second_title: "Aspose.PDF для Go через C++"
description: "Вернуть количество слов на указанной странице PDF-документа."
type: docs
url: /ru/go-cpp/core/pagewordcount/
---

_Вернуть количество слов на указанной странице в PDF-документе._

```go
func (document *Document) PageWordCount(num int32) (int32, error)
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **int32** - word count on the page
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) открывает PDF-документ с именем файла
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() освобождает выделенные ресурсы для PDF-документа
	defer pdf.Close()
	// PageWordCount(num int32) возвращает количество слов на указанной странице в PDF-документе.
	page_word_count, err := pdf.PageWordCount(1)
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Word count on the first page:", page_word_count)
}
```
