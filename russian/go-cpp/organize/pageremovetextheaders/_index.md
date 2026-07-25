---
title: "PageRemoveTextHeaders"
second_title: "Aspose.PDF для Go через C++"
description: "Удалить текстовые заголовки на странице."
type: docs
url: /ru/go-cpp/organize/pageremovetextheaders/
---

_Удалить текстовые заголовки на странице._

```go
func (document *Document) PageRemoveTextHeaders(num int32) error
```

**Parameters**: 
  * **num** - page number of the PDF-document

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
        // PageRemoveTextHeaders(num int32) удаляет текстовые заголовки на странице
        err = pdf.PageRemoveTextHeaders(1)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
        err = pdf.SaveAs("sample_page1_RemoveTextHeaders.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
