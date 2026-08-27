---
title: "PageCount"
second_title: "Aspose.PDF для Go через C++"
description: "Вернуть количество страниц в PDF-документе."
type: docs
url: /ru/go-cpp/core/pagecount/
---

_Вернуть количество страниц в PDF-документе._

```go
func (document *Document) PageCount() (int32, error)
```

**Parameters**: 

**Return**: 
  * **int32** - page count of the PDF-document
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
	// PageCount() возвращает количество страниц в PDF-документе
	count, err := pdf.PageCount()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Count:", count)
}
```
