---
title: "PageReplaceFont"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "ページのフォントを置換します。"
type: docs
url: /ja/go-cpp/organize/pagereplacefont/
---

_ページ内のフォントを置換する._

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
        // Open(filename string) は、指定したファイル名の PDF-document を開きます
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() は、PDF-document に割り当てられたリソースを解放します
        defer pdf.Close()
        // PageReplaceFont(num int32, findFontName, replaceFontName string) ページ内のフォントを置換します
        err = pdf.PageReplaceFont(1, "Times-BoldItalic", "Helvetica-Bold")
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) は以前に開いた PDFドキュメントを新しいファイル名で保存します
        err = pdf.SaveAs("sample_page1_ReplaceFont.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
