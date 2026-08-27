---
title: "OptimizeFileSize"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "画像圧縮品質でPDFドキュメントのサイズを最適化する。"
type: docs
url: /ja/go-cpp/organize/optimizefilesize/
---

_画像圧縮品質で PDF-document のサイズを最適化します._

```go
func (document *Document) OptimizeFileSize(imageQuality int32) error
```

**Parameters**: 
  * **imageQuality** - image compression quality 

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
        // OptimizeFileSize(imageQuality int32) は 画像圧縮品質で PDF-document のサイズを最適化します
        err = pdf.OptimizeFileSize(20)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) は以前に開いた PDFドキュメントを新しいファイル名で保存します
        err = pdf.SaveAs("sample_OptimizeFileSize.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
