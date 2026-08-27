---
title: "UnembedFonts"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "PDFドキュメントのフォントを埋め込み解除する。"
type: docs
url: /ja/go-cpp/organize/unembedfonts/
---

_PDFドキュメントからフォントの埋め込みを解除する._

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
        // Open(filename string) は、指定したファイル名の PDF-document を開きます
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() は、PDF-document に割り当てられたリソースを解放します
        defer pdf.Close()
        // UnembedFonts() PDFドキュメントからフォントの埋め込みを解除します
        err = pdf.UnembedFonts()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) は以前に開いた PDFドキュメントを新しいファイル名で保存します
        err = pdf.SaveAs("sample_UnembedFonts.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
