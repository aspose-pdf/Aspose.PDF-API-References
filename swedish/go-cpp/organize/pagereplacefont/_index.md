---
title: "PageReplaceFont"
second_title: "Aspose.PDF för Go via C++"
description: "Byt teckensnitt på sidan."
type: docs
url: /sv/go-cpp/organize/pagereplacefont/
---

_Ersätt teckensnitt på sidan._

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
        // Open(filename string) öppnar ett PDF-dokument med filnamn
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() frigör allokerade resurser för PDF-dokument
        defer pdf.Close()
        // PageReplaceFont(num int32, findFontName, replaceFontName string) ersätter teckensnitt på sidan
        err = pdf.PageReplaceFont(1, "Times-BoldItalic", "Helvetica-Bold")
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
        err = pdf.SaveAs("sample_page1_ReplaceFont.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
