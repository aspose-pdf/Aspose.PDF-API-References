---
title: "Crop"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "PDFドキュメントのページをトリミングする。"
type: docs
url: /ja/go-cpp/organize/crop/
---

_PDFドキュメントのページをクロップします._

```go
func (document *Document) Crop(margin float64) error
```

**Parameters**: 
  * **margin** - page margin

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
        // Crop(margin float64) PDFドキュメントのページをクロップします
        err = pdf.Crop(0)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) は以前に開いた PDFドキュメントを新しいファイル名で保存します
        err = pdf.SaveAs("sample_Crop.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
