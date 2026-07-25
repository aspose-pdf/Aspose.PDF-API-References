---
title: "RemoveTextHeaders"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "PDFドキュメントからテキストヘッダーを削除する。"
type: docs
url: /ja/go-cpp/organize/removetextheaders/
---

_PDF ドキュメントからテキストヘッダーを削除します。_

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
        // Open(filename string) は、指定したファイル名の PDF-document を開きます
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() は、PDF-document に割り当てられたリソースを解放します
        defer pdf.Close()
        // RemoveTextHeaders() は PDF ドキュメントからテキストヘッダーを削除します
        err = pdf.RemoveTextHeaders()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) は以前に開いた PDFドキュメントを新しいファイル名で保存します
        err = pdf.SaveAs("sample_RemoveTextHeaders.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
