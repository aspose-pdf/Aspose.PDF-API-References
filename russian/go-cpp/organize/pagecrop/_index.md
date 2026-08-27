---
title: "PageCrop"
second_title: "Aspose.PDF для Go через C++"
description: "Обрезать страницу."
type: docs
url: /ru/go-cpp/organize/pagecrop/
---

_Обрезать страницу._

```go
func (document *Document) PageCrop(num int32, margin float64) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **margin** - page margin

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
        // PageCrop(num int32, margin float64) обрезает страницу
        err = pdf.PageCrop(1, 11.3)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
        err = pdf.SaveAs("sample_page1_Crop.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
