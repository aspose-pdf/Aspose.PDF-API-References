---
title: "ReplaceFont"
second_title: "Aspose.PDF для Go через C++"
description: "Заменить шрифт в PDF-документе."
type: docs
url: /ru/go-cpp/organize/replacefont/
---

_Заменить шрифт в PDF-документе._

```go
func (document *Document) ReplaceFont(findFontName, replaceFontName string) error
```

**Parameters**: 
  * **findFontName** - font name to search
  * **replaceFontName** - font name to replace

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
        // ReplaceFont(findFontName, replaceFontName string) заменяет шрифт в PDF-документе
        err = pdf.ReplaceFont("Helvetica", "Courier")
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
        err = pdf.SaveAs("sample_ReplaceFont.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
