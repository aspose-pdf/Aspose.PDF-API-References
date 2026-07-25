---
title: "PageIsBlank"
second_title: "Aspose.PDF для Go через C++"
description: "Вернуть, является ли страница пустой в PDF-документе."
type: docs
url: /ru/go-cpp/core/pageisblank/
---

_Возвращает, является ли страница пустой в PDF-документе._

```go
func (document *Document) PageIsBlank(num int32) (bool, error)
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **bool** - the page is blank
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
	// PageIsBlank(num int32) возвращает, является ли страница пустой в PDF-документе.
	page_is_blank, err := pdf.PageIsBlank(1)
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("The first page is blank?:", page_is_blank == true)
}
```
