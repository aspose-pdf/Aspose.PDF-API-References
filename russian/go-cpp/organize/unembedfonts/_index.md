---
title: "UnembedFonts"
second_title: "Aspose.PDF для Go через C++"
description: "Удалить встраивание шрифтов в PDF-документе."
type: docs
url: /ru/go-cpp/organize/unembedfonts/
---

_Отвязать шрифты от PDF‑документа._

```go
func (document *Document) UnembedFonts() error
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
        // UnembedFonts() отвязывает шрифты от PDF‑документа
        err = pdf.UnembedFonts()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
        err = pdf.SaveAs("sample_UnembedFonts.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
