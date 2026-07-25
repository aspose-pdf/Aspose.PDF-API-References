---
title: "PageReplaceFont"
second_title: "Aspose.PDF для Go через C++"
description: "Заменить шрифт на странице."
type: docs
url: /ru/go-cpp/organize/pagereplacefont/
---

_Заменить шрифт на странице._

```go
func (document *Document) PageReplaceFont(num int32, findFontName, replaceFontName string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
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
        // PageReplaceFont(num int32, findFontName, replaceFontName string) заменяет шрифт на странице
        err = pdf.PageReplaceFont(1, "Times-BoldItalic", "Helvetica-Bold")
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
        err = pdf.SaveAs("sample_page1_ReplaceFont.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
