---
title: "PageRemoveWatermarks"
second_title: "Aspose.PDF для Go через C++"
description: "Удалить водяные знаки на странице."
type: docs
url: /ru/go-cpp/organize/pageremovewatermarks/
---

_Удалить водяные знаки на странице._

```go
func (document *Document) PageRemoveWatermarks(num int32) error
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
        // PageRemoveWatermarks(num int32) удаляет водяные знаки на странице
        err = pdf.PageRemoveWatermarks(1)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
        err = pdf.SaveAs("sample_page1_RemoveWatermarks.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
