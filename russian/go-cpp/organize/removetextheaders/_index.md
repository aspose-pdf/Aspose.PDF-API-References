---
title: "RemoveTextHeaders"
second_title: "Aspose.PDF для Go через C++"
description: "Удалить текстовые заголовки из PDF-документа."
type: docs
url: /ru/go-cpp/organize/removetextheaders/
---

_Удалить текстовые заголовки из PDF-документа._

```go
func (document *Document) RemoveTextHeaders() error
```

**Parameters**: 

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
        // RemoveTextHeaders() удаляет текстовые заголовки из PDF-документа
        err = pdf.RemoveTextHeaders()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
        err = pdf.SaveAs("sample_RemoveTextHeaders.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
