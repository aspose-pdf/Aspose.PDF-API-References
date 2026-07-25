---
title: "PageReplaceFont"
second_title: "Aspose.PDF untuk Go via C++"
description: "Ganti font di halaman."
type: docs
url: /id/go-cpp/organize/pagereplacefont/
---

_Ganti font di halaman._

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
        // Open(filename string) membuka PDF-dokumen dengan nama file
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
        defer pdf.Close()
        // PageReplaceFont(num int32, findFontName, replaceFontName string) mengganti font di halaman
        err = pdf.PageReplaceFont(1, "Times-BoldItalic", "Helvetica-Bold")
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) menyimpan PDF-document yang sebelumnya dibuka dengan nama file baru
        err = pdf.SaveAs("sample_page1_ReplaceFont.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
