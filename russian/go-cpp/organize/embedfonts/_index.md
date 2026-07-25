---
title: "EmbedFonts"
second_title: "Aspose.PDF для Go через C++"
description: "Встроить шрифты в PDF-документ."
type: docs
url: /ru/go-cpp/organize/embedfonts/
---

_Встроить шрифты в PDF-документ._

```go
func (document *Document) EmbedFonts() error
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
        // EmbedFonts() встраивает шрифты в PDF-документ
        err = pdf.EmbedFonts()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
        err = pdf.SaveAs("sample_EmbedFonts.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
