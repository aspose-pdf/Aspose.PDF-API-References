---
title: "ReplaceFont"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "PDFドキュメントのフォントを置換する。"
type: docs
url: /ja/go-cpp/organize/replacefont/
---

_PDF ドキュメント内のフォントを置換します。_

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
        // Open(filename string) は、指定したファイル名の PDF-document を開きます
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() は、PDF-document に割り当てられたリソースを解放します
        defer pdf.Close()
        // ReplaceFont(findFontName, replaceFontName string) は PDF ドキュメント内のフォントを置換します
        err = pdf.ReplaceFont("Helvetica", "Courier")
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) は以前に開いた PDFドキュメントを新しいファイル名で保存します
        err = pdf.SaveAs("sample_ReplaceFont.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
